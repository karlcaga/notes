# Aug 28
- Complete parser implementation for expressions (v0.0.4)
- Update pplox_web with finished parser
- Begin writing expression evaluation by evaluating booleans and nil

# Aug 26
- Add support for parsing parenthesized groups
- Play with HTML 

# Aug 25
- Add structure to pplox_web 
- Add more details to pplox readme
- Add `--parse` option to pplox CLI

# Aug 24
- Added support for parsing strings and numbers

# Aug 23
- Added parser (v0.0.3)
- Added parser to pplox_web
- Moved pplox_web docs to material-mkdocs
- Moved pplox_web docs from ReadTheDocs to GitHub Pages
- Wrote changelog for pplox_web using material-mkdocs blog plugin
- Made GitHub Action for deploying to GitHub Pages

# Aug 21
- Add readthedocs for pplox_web

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

# August 14
- Created Django app to run pplox on web.
- Web app has 2 URLs.
    The root shows the form for input.
    `/interpreter/runcode/` takes a `POST` request with a `code` parameter and outputs the tokenized version.
- Deployed with Render.

# August 11
- Add docs and automated test to pplox
- Released version 0.0.1 and 0.0.2 giving it full tokenizer