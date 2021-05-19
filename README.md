# flask-sockets-google-speech-api
A simple demo in order to run google speech api on a flask backend with a websocket streaming audio input

In order to test this:
1. python3 -m venv venv #Create a virtual environment
2. source venv/bin/activate #Activate the environment
3. pip install -r requirements.txt #Install dependencies
4. Place your google cloud speech api credentials at ./credentials.json
5. python websocket_server.py #Start the server
6. Go to http://localhost:8000/ and start speaking
