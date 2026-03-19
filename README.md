# Install

```bash
sudo apt install ruby-dev ruby-bundler nodejs
bundle config set --local path 'vendor/bundle'
bundle install
```

# Local Serve

To serve the website locally, run the following command in the root directory of the repository:

```bash
bundle exec jekyll serve -l -H localhost
```
