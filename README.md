# Rueditas

Rueditas is the base Rails application template used at [Hash Labs](https://www.hashlabs.com)

![rueditas](http://mla-s1-p.mlstatic.com/bicicletas-halley-para-ninos-19057-playera-rueditas-rod-16-13682-MLA87487077_3161-O.jpg)

## Usage

```bash
git clone https://github.com/hashlabs/rueditas
rails new app_name -T -m rueditas/template.rb
```

## Gemfile

This template include additional gems that we use to kickstart our Rails projects. Here's a list of the gems included.

* [Autoprefixer Rails](https://github.com/ai/autoprefixer-rails) for CSS vendor prefixes
* [Airbrake](https://github.com/airbrake/airbrake) for exception notification
* [Bootstrap SASS](https://github.com/twbs/bootstrap-sass) for css and
  markup
* [New Relic RPM](https://github.com/newrelic/rpm) for monitoring performance
* [Normalize](https://necolas.github.io/normalize.css/) for resetting browser styles
* [Postgres](https://github.com/ged/ruby-pg) for access to the Postgres database
* [Rack Canonical Host](https://github.com/tylerhunt/rack-canonical-host) to
  ensure all requests are served from the same domain
* [Rack Timeout](https://github.com/heroku/rack-timeout) to abort requests that are
  taking too long
* [Recipient Interceptor](https://github.com/croaky/recipient_interceptor) to
  avoid accidentally sending emails to real people from staging
* [React Rails](https://github.com/reactjs/react-rails) for great Front-end components
* [SASSC Rails](https://github.com/sass/sassc-rails) to compile SCSS
  files faster using libsass
* [Simple Form](https://github.com/plataformatec/simple_form) for form markup
  and style
* [Puma](https://github.com/puma/puma) to serve things

And development gems like:

* [Dotenv](https://github.com/bkeepers/dotenv) for loading environment variables
* [Pry Rails](https://github.com/rweng/pry-rails) for interactively exploring
  objects
* [ByeBug](https://github.com/deivid-rodriguez/byebug) for interactively
  debugging behavior
* [Bullet](https://github.com/flyerhzm/bullet) for help to kill N+1 queries and
  unused eager loading
* [Bundler Audit](https://github.com/rubysec/bundler-audit) for scanning the
  Gemfile for insecure dependencies based on published CVEs
* [Spring](https://github.com/rails/spring) for fast Rails actions via
  pre-loading
* [Web Console](https://github.com/rails/web-console) for better debugging via
  in-browser IRB consoles.

## License

Rueditas is Copyright © 2014-2016 Hash Labs. It is free software, and may be redistributed under the terms specified in the [LICENSE](/LICENSE) file.

## About Hash Labs

![hash labs logo](https://www.hashlabs.com/images/hashlabs_logo_horizontal_02.png)

Rueditas is maintained by [Hash Labs LLC](https://www.hashlabs.com)
