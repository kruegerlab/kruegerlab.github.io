# Lab Website (in progress)
This site uses the feeling-responsive Jekyll theme; view the theme docs for customization tips.

## Add your name to `/people`
To add your name to the people page,
1. Edit `/_data/people.yml` to add your name and info in the same format as theother entries.
2. Add your profile pic to `/images/people`

## Instructions to build the site locally
If you want to make changes to the site, it's useful to clone this repo and build the site locally. Here's how:

* Install ruby and gem (eg `sudo apt install ruby-full`)
* Clone this repository and cd into it
* Run `gem install bundler jekyll` to install jekyll
* Run `bundle install` to install the theme prerequisites
* To build the website locally, run `bundle exec jekyll serve`


More documentation here: https://jekyllrb.com/
