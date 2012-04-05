```
Purpose:
Get names of people with late timesheets
Contact people who have late timesheets

To see options:
jcvd --help

To use:
tec --region desired_region | jcvd --call

or

tec > file
jcvd --email file

in the us:
tec --region us | jcvd --email
or
tec --region us | jcvd --email --sms

default region is australia (au) 

See setup_template.sh for environment variables that must be set in order to run the app. 

You will need a Twilio account to make phone calls.
Twillio pricing: https://www.twilio.com/pricing

Data to be fed into jcvd is in format
{"name":"a","email":"a@b.com","mobile":"c"}

```
