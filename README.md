# flask-sockets-google-speech-api
A simple demo in order to run google speech api on a flask backend with a websocket streaming audio input

In order to test this:
1. python3 -m venv venv #Create a virtual environment
2. source venv/bin/activate #Activate the environment
3. pip install -r requirements.txt #Install dependencies
4. Place your google cloud speech api credentials at ./credentials.json
5. python websocket_server.py #Start the server
6. Go to http://localhost:8000/ and start speaking


I adapted the server code from https://github.com/dawntcherian/Google-speech-to-text-python-websocket-server-using-microphone-stream and just added the flask_sockets server and the landing page from https://gist.github.com/cobookman/6459f0423d56527ad136999e57d181ea.
