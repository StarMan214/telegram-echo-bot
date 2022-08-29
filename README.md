# telegram-echo-bot

 A simple telegram bot made in javascript to echo your own messages

Steps to Deploy this Bot Using Ngrok : 
1. install ngrok then go to its console and use the below commands to install the dependencies -

npm init
npm i --save express
npm i --save body-parser
npm i --save axios
npm i --save dotenv
npm i --save-dev nodemon

2. After installing all of the above head over to the botfather bot in telegram and create a new bot for yourself which we will use with this
3. Copy the bot's token and paste it into the .env file 
4. Host your localserver using ngrok (open ngrok and type ngrok http 5000/any other port you want)
5. Copy the server link from ngrok and paste it into the .env file
6. After everything is done head over to ngrok again and type - npm run dev
7. Well everything's pretty much ready head over to the bot you made using botfather and type any messages 
