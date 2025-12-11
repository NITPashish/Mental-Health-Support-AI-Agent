# Mental-Health-Support-AI-Agent
You can  interact with our AI agent through whatsapp chat as well through the webpage. If my agent found that user's  very depressed or intending for self harm, it will automatically trigger a call to the mental health dept with the users info (like location,etc).

Frontend: whatsapp chat (using twilio) and streaming for web experience 
Tools: 
1 Emergency call trigger (mental health helpline or any other emergency call contracts provided) in case it detects user is intending for self harm (like suicidal things)
2. In case of general mental health related topic, it will use medgemma(trained on medical data) to make provide mannerful consultation by taking care of the user's mentel health
3. third tool uses Google map places api to provide details of top 5 mental health specialist as per user's location.
Backend: FastAPI 
ngrok for exposing the port so that backend gets connected with whatsapp chat.
