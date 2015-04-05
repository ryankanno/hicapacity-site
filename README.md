### Overview

Jekyll based site for [hicapacity.org](http://hicapacity.org), a
hackerspace/makerspace from Honolulu, HI. Previous version was in Wordpress
and we are currently migrating.

### Development

#### Vagrant

`vagrant up`

open your browser to http://127.0.0.1:4000

The included Vagrantfile will install all the dependencies, create a screen
session named Jekyll and run the following Jekyll command:

`jekyll serve -P 4000 --host 0.0.0.0 --watch --force_polling`

#### Roll-your-own

[Ruby](https://www.ruby-lang.org) 2.2.0 is needed for Jekyll.
[Jekyll](https://github.com/mojombo/jekyll) is needed to generate the site.

Install dependencies:

    $ bundle

Run the site locally:

    $ jekyll serve

For development use --watch to refresh upon write:
    
    $ jekyll serve --watch
    
See [https://github.com/mojombo/jekyll/wiki/configuration](https://github.com/mojombo/jekyll/wiki/configuration) for all configuration options.

### Contact

Github: [wangbus](http://github.com/wangbus) [jsakuda](https://github.com/jsakuda)
Twitter: [@wangbus](http://twitter.com/wangbus)
