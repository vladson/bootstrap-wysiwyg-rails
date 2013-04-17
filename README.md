# Bootstrap Wysiwyg Rails

[Bootstrap-wysihtml5][bootstrap-wysiwyg] is a javascript plugin that makes it easy to create simple, beautiful wysiwyg editors with the help of [wysihtml5][wysihtml5] and [Twitter Bootstrap][twitter-bootstrap].

[bootstrap-wysiwyg]: https://github.com/jhollingworth/bootstrap-wysihtml5
[wysihtml5]: https://github.com/xing/wysihtml5
[twitter-bootstrap]: http://twitter.github.com/bootstrap

For customizing and more - look at js repo

## Installation

Add this line to your application's Gemfile:

    gem 'bootstrap-wysiwyg-rails'

And then execute:

    $ bundle install

Be sure to have all dependencies in your project. They include

    jquery
    twitter-bootstrap
    jquery.hotkeys

They where not included in gem dependencies because you already may have them in your assets somehow.

## Usage

Require bootstrap-wysiwyg in your app/assets/application.js file

    //= require bootstrap-wysiwyg

Initialize it on element

    $('#editor').wysiwyg()

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
