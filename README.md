August 16
Create pplox_web more prod ready with env vars for secrets. ***HSTS is scary!!!!!!!!!!!!!!!!!!!!!!!!!!!***
Created Dockerfile for running pplox.
Create GitHub Action to build and push Docker container to GHCR.
Update pplox version on pplox_web to 0.0.2 and deployed to Render giving it full tokenizer.

August 14
Created Django app to run pplox on web.
Web app has 2 URLs.
    The root shows the form for input.
    `/interpreter/runcode/` takes a `POST` request with a `code` parameter and outputs the tokenized version.
Deployed with Render.

August 11