# Heroku Buildpack for webpack

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for web applications that use webpack.

## Usage

The `bin/compile` script run webpack with a specially named configuration file (`webpack.heroku.config.js` in your main directory). To use the buildpack:

1. Configure as your second buildpack:

   ```bash
   $ heroku buildpacks:add --index 2 https://github.com/tweettypography/heroku-buildpack-webpack
   ```

2. Deploy to Heroku.
