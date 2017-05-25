This is the repo for the exercise project to be developed in Shanghai team's Modern Mobile Development course

# Installation
Please install the following tools for this project. The latest version should be fine unless specific version is listed.

* git
* mysql
* ruby 2.4
* Rubymine (or any editor you preferred for ruby development)

# Setup Command Line Development Environment
Use git to clone this project into a folder. Then in this folder, run the command below in order.

* Create a default mysql dba user `mysql -u root -p < sql/create_default_dba.sql`
* Init environment `gem install bundler; bundle install; rake db:create; rails db:migrate`
* Start Web Application `rails s` (on port 3000)

# Tips for Mac installation
Here are some tips for Mac installations.
* [Homebrew](http://brew.sh/) is recommended for Mac tool and app installations
    * Tools and services can be installed via, for example, `brew install git`
    * Applications can be installed via, for example, `brew cask install genymotion`
    
# Tips for Windows installation
Here are some tips for Windows installations.
* Please consider to install [Babun](http://babun.github.io/) and then install command line tools like git and rvm in it
