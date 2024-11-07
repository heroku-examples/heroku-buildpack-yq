# Heroku Buildpack YQ

An example classic Heroku buildpack for `yq`. It installs the `yq` binary so that `json`, `yaml`, and `toml` files may be parsed from the command line.

This buildpack is for informational purposes only and is not officially supported!

Add to your Heroku app with

```
$ heroku buildpacks:add https://github.com/heroku-examples/heroku-buildpack-yq
--index 1
```
