# Build Dockerfile
`docker build .`

# Run Dockerfile
`docker run -it --net=host -e PPLOX_WEB_SECRET_KEY=iuhyqwsiudty18976e19873641987c6 -e PPLOX_WEB_DEBUG=True <IMAGE_ID>` 