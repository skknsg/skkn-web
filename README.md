# SKKN Website Content

## Development

- Need Linux/Mac with Podman installed
- Recommended to use VSCode editor
- Test the website locally using Jekyll container - sample below:

```shell
$ podman run --rm -p 4000:4000 -v ${PWD}:/data:Z -it quay.io/iamgini/jekyll-dev:1.0 sh -c "bundle install && bundle exec jekyll serve --host 0.0.0.0 --incremental"
```

### Updating content

- Create and GitHub account and contact admin (to be confirmed)
- a) You can clone and update from local machine if you have a development environment as explained above
- b) You can edit from GitHub WEBUI IDE and commit (Save) it.
- The content will be updated to the site automatically using backend build pipelines.
- Please DO NOT edit any configurations, CSS, HTML files as it may break the site configuration. Contact the admin if you are not sure about the edits.