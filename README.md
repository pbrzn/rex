# RexMovieRecommendationBot

Sick of endlessly scrolling Netflix, Hulu, or countless other streamers looking for the right movie to watch?
Just ask Rex! Rex is a bot designed to collate the top 30 most popular movies offered by the streaming service of your choice, then give you a recommendation, either from the full list or from the specific genre you wish to explore.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'rex_movie_recommendation_bot'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install rex_movie_recommendation_bot

## Usage

First, you will be prompted to name a streaming service of your choice, such as Netflix, Disney Plus, Amazon Prime Video, etc.

Once you have typed your choice into the CLI, you will be given be given the choice of either listing the 30 most popular movies on the service, choosing a genre, or get a recommendation right off the bat.

Once you have made your choice you will either receive your recommendation or be given prompts to facilitate your recommendation. When you receive your recommendation you will be asked whether you would like another recommendation, start fresh with a different streaming service, or end the program.

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/pbrzn/rex_movie_recommendation_bot. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/pbrzn/rex_movie_recommendation_bot/blob/master/CODE_OF_CONDUCT.md).

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the RexMovieRecommendationBot project's codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/pbrzn/rex_movie_recommendation_bot/blob/master/CODE_OF_CONDUCT.md).
