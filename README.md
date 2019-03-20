# heroku-connect-api--documentation

## Project setup:

```
# git clone https://github.com/skplunkerin/heroku-connect-api--documentation.git
# cd heroku-connect-api--documentation/
bundle install

# make sure you have middleman installed
gem install middleman
```

## Local dev server:

```
# cd heroku-connect-api--documentation/
middleman server

# To check server options
middleman server --help
```

## Deploy:

### For compiling code to host:
```
middleman build
```

### Build/Host on gh pages
[skplunkerin.github.io/heroku-connect-api--documentation](https://skplunkerin.github.io/heroku-connect-api--documentation/)

```
# Compile all files into the build directory
rake build

# Build and publish to Github Pages
rake publish
```

For help with publishing to Github Pages, see: https://github.com/edgecase/middleman-gh-pages
