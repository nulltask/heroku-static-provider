# Heroku Static Provider

Static site provider for Heroku.


## Installation

You need sign-in or sign-up to Heroku.

    $ git clone https://github.com/nulltask/heroku-static-provider.git my-site
    $ cd my-site
    $ heroku create
    $ git push -u heroku master
    $ heroku open

## Deployment

Add or update files in `/public`.

    $ git add .
    $ git commit -a -m 'some commit message'
    $ git push heroku master
    $ heroku open

## Notes

### Adding Basic Auth

	$ heroku config:set USER=username
	$ heroku config:set PASS=password

### Screencast

  * https://vimeo.com/71315109

## License

MIT
