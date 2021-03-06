# rabelyoda

A simple utility to push/pull l10n resources of a Rails project to/from the translators.

## Hot to Install

    sudo gem install rabelyoda

## How to Use

    cd your-rails-project-dir
    rabelyoda

Checkout the `config/locales.out` folder for merged locale files. Each file, except the `en.yml`, will have new strings added with `[pls translate]` in the beginning. 

All of the strings not found in `en.yml`, will be removed from `*.yml` as well.

You can then give all these `locale.yml` files to your translators. When the translation is done just copy the translated file over the original one in `config/locales`, commit and deploy.

## Note on Patches/Pull Requests
 
* Fork the project.
* Make your feature addition or bug fix.
* Add tests for it. This is important so I don't break it in a
  future version unintentionally.
* Commit, do not mess with rakefile, version, or history.
  (if you want to have your own version, that is fine but bump version in a commit by itself I can ignore when I pull)
* Send me a pull request. Bonus points for topic branches.

## Copyright

Copyright (c) 2010 Andrey Subbotin. See LICENSE for details.
