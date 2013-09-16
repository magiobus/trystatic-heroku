#trystatic-heroku is a config.ru file to upload static pages to heroku using ruby rack.

#How to use:

just go to https://devcenter.heroku.com/articles/static-sites-ruby
and read how to upload a static page to heroku.

instead of using config.ru file configuration in heroku's page
use this one to use urls between pages.

#UrlExample:

index.html = /

page2.html = /page2

404.html = any page that doesn't exist

standalone version of Ryan Tomayko's TryStatic, originally part of Rack-Contrib gem.
https://github.com/rack/rack-contrib/blob/master/lib/rack/contrib/try_static.rb

