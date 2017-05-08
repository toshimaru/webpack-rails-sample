# webpack-rails sample application

- Rails 5.1
- :gem: webpack-rails
- rails new with `--skip-sprockets`

## Functionality

- run servers with foreman in development
- Use `javascript_include_tag`
- webpack + webpack-dev-server

## Run development servers

```
$ foreman start
```

## Test production mode from localhost

```
$ RAILS_SERVE_STATIC_FILES=on SECRET_KEY_BASE=xxx RAILS_ENV=production foreman start
```
