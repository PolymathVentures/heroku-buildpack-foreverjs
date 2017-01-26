# Heroku Buildpack for Forever JS support

This buildpack will install forever js (https://github.com/foreverjs/forever) globally (with npm install -g), and install node and npm if needed.

## Usage

Creating a new Heroku instance from an Ember CLI application's parent directory:

    $ heroku create --buildpack <github_url_for_this_buildpack>

    $ git push heroku master
    ...
    -----> Heroku receiving push
    -----> Fetching custom buildpack
    ...

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Contributors

If you contribute, you will be mentioned here :)
