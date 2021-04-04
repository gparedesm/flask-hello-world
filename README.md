# flask-hello-world

Flask application in with you can obtain "Hello World" message with the main path. You add /hello/<name> you.
  
## Docker
If you clone this repository, you can dockerize this app running this comamand:
`docker build -t flask-hello .`

Then:
`docker run --name flask-app --rm -d -p 80:80 flask-hello`

### Docker Hub
You can only pull it from dockerhub, and run it.
`docker pull gpm0009/flask-hello-world`
