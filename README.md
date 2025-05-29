# SKKN Website Content

## Development

- Need Linux/Mac with Podman installed
- Recommended to use VSCode editor
- Test the website locally using Jekyll container - sample below:

```shell
$ podman run --rm -p 4000:4000 -v ${PWD}:/data:Z -it quay.io/iamgini/jekyll-dev:1.0 sh -c "bundle install && bundle exec jekyll serve --host 0.0.0.0 --incremental"
```
