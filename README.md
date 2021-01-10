# heroku-buildpack-borrowmi

Deletes the node_modules and src folders to decrease slug size.

## Usage

    $ heroku buildpacks:set https://github.com/jnutkins91/heroku-buildpack-borrowmi.git

Or add it to the .buildpacks file if using [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi):

    $ cat .buildpacks
    ...
    https://github.com/jnutkins91/heroku-buildpack-borrowmi.git
