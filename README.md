The chat application I wrote with Django's Channels Library and JavaScript's PeerJS library. Django Channels and WebSockets are used for written communication. PeerJS and WebRTC are used in video and audio communication. While you can share image and audio files with the application, it is also possible to record audio and send it to the other party.

Requirements:

pip install -r requirements.txt

python manage.py makemigrations

python manage.py migrate

python manage.py runserver

(Required for NodeJS and NPM for PeerServer to work at the back)

npm install
npx peerjs --port 9000 (launch peer server)
