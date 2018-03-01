
# Send an SMS Message with Kotlin in 30 Seconds
This is the repository for the Twilio blog article on sending an SMS message with Kotlin in 30 seconds

## Running
Make sure you have the following environment variables defined:

- `TWILIO_ACCOUNT_SID`: Your Twilio account SID from [The Twilio Console](https://www.twilio.com/console)
- `TWILIO_AUTH_TOKEN`: Your Twilio Auth Token from [The Twilio Console](https://www.twilio.com/console)
- `MY_NUMBER`: Your mobile phone number
- `TWILIO_NUMBER`: your Twilio telephone number which you can get [here](https://www.twilio.com/console/phone-numbers/incoming)

### Building a *.jar file
From the folder where your files are run `./gradlew clean build` on your terminal

### Executing the *.jar file
From the same terminal screen run `java -jar build/libs/TwilioSMS30Seconds-1.0-SNAPSHOT.jar`
