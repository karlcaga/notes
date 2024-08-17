# Aug 17
- Use Gunicorn for production server inside of Docker
- Create GCE instance to deploy pplox_web
- Create GitHub Action to deploy pplox_web on GCE using service account and SSH
- Add concurrency check to GitHub Action https://github.com/karlcaga/pplox_web/commit/8729e13d2cc68544b7ebaffc0e9fcc170533b21e
- HTML cleanup
- Print out env vars with f-strings ```print(f"{ASD=})```

# August 16
- Create pplox_web more prod ready with env vars for secrets. ***HSTS is scary!!!!!!!!!!!!!!!!!!!!!!!!!!!***
- Created Dockerfile for running pplox.
- Create GitHub Action to build and push Docker container to GHCR.
- Update pplox version on pplox_web to 0.0.2 and deployed to Render giving it full tokenizer.

August 14
- Created Django app to run pplox on web.
- Web app has 2 URLs.
    The root shows the form for input.
    `/interpreter/runcode/` takes a `POST` request with a `code` parameter and outputs the tokenized version.
- Deployed with Render.

August 11
Add docs and automated test to pplox
Released version 0.0.1 and 0.0.2 giving it full tokenizer