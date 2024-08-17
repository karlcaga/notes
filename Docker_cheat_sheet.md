# Build Dockerfile
`docker build .`


# Run Dockerfile
`docker run -it -e PPLOX_WEB_SECRET_KEY=$PPLOX_WEB_SECRET_KEY -e PPLOX_WEB_DEBUG=$PPLOX_WEB_DEBUG -e PPLOX_WEB_SECURE_SSL_REDIRECT=$PPLOX_WEB_SECURE_SSL_REDIRECT --expose 8002 -p 8002:8000 <IMAGE_ID>` 
THIS IS NOT MY SECRET KEY super duper promise 🐍