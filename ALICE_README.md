# CHALLENGE SUMMARY


# HOW TO PLAY THE GAME



# APPROACH

## Set-up (tech)
- file structure
- development environment
- resources

## Planning
- Model View Controller (MVC)
  - Mapping out

***
## SET-UP
## File Structure
RPS-Challenge
|-_Gemfile
|-_app.rb
|-_config.ru
|-_spec
  |-spec_helper.rb
  |-\__features
    |web_helpers.rb
|-_views
|-_lib

## Development Environment
Run Makers init
`makersinit`
Added Selenium
- Gemfile -> `gem 'selenium-webdriver'`
Run bundle
- `bundle install`
Update bundle
- `bundle update`
Pry
~~~~
require "capybara/dsl"
require "selenium-webdriver"
include Capybara::DSL
Capybara.default_driver = :selenium
rackup -p [9292 - check]
~~~~

## Resources