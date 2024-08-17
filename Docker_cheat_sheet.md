# Build Dockerfile
`docker build .`


# Run Dockerfile
`docker run -it -e PPLOX_WEB_SECRET_KEY=<RANDOM_STRING> -e PPLOX_WEB_DEBUG=True -e PPLOX_WEB_SECURE_SSL_REDIRECT=False --expose 8000 -p 8000:8000 <IMAGE_ID>` 
THIS IS NOT MY SECRET KEY super duper promise 🐍