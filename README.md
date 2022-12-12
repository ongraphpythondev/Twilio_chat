# Chat apps with Twilio
This sample project demonstrates how to use Twilio APIs in a Django. Once the app is up and running, check out the home page to see which demos you can run. You'll find examples for Chat in the images below.

Let's get started!
  
# Prerequisites
You will need the following programmes properly installed on your computer.<br>
Python 3.7+

# Installation and Running

clone the repository
```
git clone https://github.com/ongraphpythondev/Twilio_chat.git
cd Twilio_chat
```
create a vertual environment
```
python -m venv .venv
.venv/bin/activate.bat
```
install required packages
```
pip install -r requirements.txt
```
running
```
python manage.py runserver
```

# Configure account information

Every sample in the demo requires some basic credentials from your Twilio account. Configure these first in setting.py .

| Config Value  | Description |
| :-------------  |:------------- |
`TWILIO_ACCOUNT_SID` | Your primary Twilio account identifier - find this [in the console here](https://www.twilio.com/console).
`TWILIO_API_KEY` | Used to authenticate - [generate one here](https://www.twilio.com/console/dev-tools/api-keys).
`TWILIO_API_SECRET` | Used to authenticate - [just like the above, you'll get one here](https://www.twilio.com/console/dev-tools/api-keys).
`TWILIO_CHAT_SERVICE_SID`  | Generate one in the [Twilio Chat console](https://www.twilio.com/console/chat/services)

