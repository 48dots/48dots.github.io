# 48dots.github.io

> This is the Github repo containing code for the 48dots homepage, hosted using [Github Pages](https://pages.github.com/)

## About

The page is built using the [Jekyll](http://jekyllrb.com/) templating system, combined with the [Bootstrap](http://getbootstrap.com/) framework ([SASS branch](https://github.com/twbs/bootstrap-sass)), [FontAwesome](http://fortawesome.github.io/Font-Awesome/) and [Masonry](https://github.com/desandro/masonry).

## Build Instructions

This project was built in Windows, so these instructions cater towards Windows systems. However, all the dependencies should have Linux equivalents and can be adapted appropriately.
### Ruby 
Ruby and the Ruby DevKit can be installed using the instructions [here](http://jekyll-windows.juthilo.com/1-ruby-and-devkit/). Alternately it can be installed in [Chocolatey](https://chocolatey.org/) with the command 'choco install ruby -y'
### Jekyll
Jekyll can be configured with the Github Pages dependencies. This will allow building and serving the website locally to preview exactly how it will be seen once hosted on Github Pages.
First, install bundler using the command 'gem install bundler'
My Gemfile contains the appropriate dev dependencies. Simply navigate to the cloned repository and run 'bundle install'

Now, simply run 'jekyll serve --watch' in the root of the repository, and visit http://localhost:4000 in your browser to see the page. The watch tag means that the page will regenerate automatically as changes to the source are made.

## Staying Updated
Run 'bundle update' from the root of the repository to keep Jekyll and it's dependencies up to date.

