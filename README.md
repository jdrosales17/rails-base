# Rails 7 Template

Rails Base is a boilerplate project with [Hotwire](https://hotwired.dev/) and [Tailwind CSS v3.0](https://tailwindcss.com/) for full stack Rails applications with a modern SPA-like experience. It is based on Rails 7 and Ruby 3.1.0.

## How to use

1. Clone this repo
1. Install PostgreSQL in case you don't have it
1. Run `bundle install`
1. Setup the database with `rails db:setup`
1. Run `rspec` and make sure all tests pass
1. To run the server use the command `bin/dev` which also watches for changes in the CSS files
1. You can now try your app in `http://localhost:3000/`

## Gems

- [Annotate](https://github.com/ctran/annotate_models) for documenting the schema in useful classes
- [Brakeman](https://github.com/presidentbeef/brakeman) for detecting security vulnerabilities via static analysis
- [Bullet](https://github.com/flyerhzm/bullet) for detecting N+1 queries and unused eager loading
- [Dotenv](https://github.com/bkeepers/dotenv) for handling environment variables
- [Factory Bot](https://github.com/thoughtbot/factory_bot) for generating test data
- [Faker](https://github.com/stympy/faker) for generating fake data
- [Letter Opener](https://github.com/ryanb/letter_opener) for previewing mail in the browser
- [Puma](https://github.com/puma/puma) for the server
- [RSpec](https://github.com/rspec/rspec) for testing
- [Rubocop](https://github.com/bbatsov/rubocop/) for Ruby linting
- [Shoulda Matchers](https://github.com/thoughtbot/shoulda-matchers) for testing
- [Simplecov](https://github.com/colszowka/simplecov) for code coverage

## Optional configuration

- Configure your timezone accordingly in `application.rb`
