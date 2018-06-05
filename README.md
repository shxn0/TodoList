# Todolist
* Task Management application
* Intuitive button layout to switch each task of status
* Being able to search your undone tasks

#### Development environment
* Rails version: 5.1.6
* Ruby version: 2.5.0 (x86_64-darwin16)

## Technical elements

#### Rubygems (except default gems on rails 5.1)
* better_errors
* dotenv-rails
* pry-rails
* rails_12factor
* bundler

#### Package Management Tool
#### Others
* heroku
* Ajax
* PostgreSQL 9.6.4
* homebrew
* yarn

## Description

## Setup procedure (development environment)

### Required elements and explanation

1. `homebrew` Make it easier to install software into Mac OS
2. `rbenv` Required to switch Ruby versions *(installed via homebrew)*
3. `Ruby` Operated by rbenv *(installed via rbenv)*
4. `Rubygems` Library packaging and distribution for Ruby
5. `Bundler` Manage gems and its version for each your projects *(gem)*
6. `PostgreSQL` *(Database)*


#### Install homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

#### Uninstall standard equipment Ruby
```
which ruby (If path has been displayed, Ruby has already been installed.)
sudo port uninstall ruby
```

#### upgrade homebrew
```
brew upgrade
```

#### Install rbenv and ruby-build to managing Ruby versions
```
brew install rbenv ruby-build
```

#### Set up rbenv 
```
echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
```

#### Install Ruby
```
rbenv install 2.5.0
ruby -v (If its version has been displayed, Ruby has already been installed.)
```

#### set up default Ruby version
```
rbenv global 2.5.0
```

#### Install Bundler
```
gem install bundler
```

#### Install Rails 5
```
gem install rails -v 5.1.6
```

#### Install PostgreSQL
```
brew install postgresql
```

#### Start PostgreSQL (Only once for an application)
```
brew services start postgresql
```

#### install Git
```
brew install git
```

#### install heroku
```
brew install heroku
```


```print "test" ```

***

`test2`

1. List1
  1. List1-1
  1. List1-2

  [Google](https://www.google.co.jp/)

  Hello *World* Italic  
  Hello **World** Bold  
  Hello ***World*** Italic & Bold
