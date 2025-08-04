How it works

1. When you push code to GitHub, the pipeline starts.
2. It installs needed packages and runs tests.
3. It builds a Docker image of your app.
4. It sends (pushes) the image to Docker Hub.
5. It connects to your EC2 server and runs the Docker container.
