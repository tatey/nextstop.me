# Next Stop

This is the website of http://nextstop.me.

## Installation

Clone the repository and bootstrap.

    $ cd nextstop.me
    $ _script/bootstrap

Serve.

    $ _script/serve

## Deploy

Configure _jekyll_s3.yml. See [jekyll-s3 for more information](https://github.com/laurilehmijoki/jekyll-s3).

Configure bucket.

    $ [bundle exec] configure-s3-website --config-file _jekyll_s3.yml

Deploy.

    $ _script/deploy

## Copyright

Copyright © Tate Johnson.

All files, directories and their contents are copyright Tate Johnson. You may
not reuse anything therein without permission.
