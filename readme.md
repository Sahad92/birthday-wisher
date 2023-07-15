# Birthday Email Sender

This Python script sends automated birthday emails to contacts whose birthdays match the current date. It reads birthday information from a CSV file and uses letter templates to personalize the emails. The script utilizes the SMTP protocol to send emails through your email provider.


## Update

Update the following variables in the code:

- `MY_EMAIL`: Replace with your own email address.
- `MY_PASSWORD`: Replace with your email password.
- `YOUR EMAIL PROVIDER SMTP SERVER ADDRESS`: Replace with the SMTP server address provided by your email provider.
  - Example: SMTP server address for Gmail: `"smtp.gmail.com"`


- Make sure your email provider allows less secure apps to access your account. Adjust the settings accordingly.

 Update the `birthdays.csv` file:

- Add the birthdays of the contacts you want to send emails to, with the format `name,email,year,month,day`.
- Make sure to update the CSV file with today's month and day for testing.


## Customization

- Letter Templates: You can create multiple letter templates in plain text format inside the `letter_templates` folder. The script will randomly select one of these templates for each birthday email.

- CSV File Format: Make sure the `birthdays.csv` file follows the format `name,email,year,month,day` for each entry.

## Prerequisites

- Python 3.x
- Pandas library (`pip install pandas`)
