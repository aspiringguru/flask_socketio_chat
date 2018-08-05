This code goes along with this video: https://youtu.be/RdSrkkrj3l4

https://www.youtube.com/watch?v=RdSrkkrj3l4


It covers a simple SocketIO app in Flask.


setup

git clone https://github.com/PrettyPrinted/flask-socketio-chat.git

#check if required flask packages installed
pip freeze | grep ask

pip install Flask
pip install Flask-SocketIO

We use this instead of usual Flask run because we need sockets real time functionality.
socketio.run(app)


@socketio.on   listens for message
