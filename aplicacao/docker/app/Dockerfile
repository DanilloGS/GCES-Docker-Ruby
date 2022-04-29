FROM ruby:3.0.0

RUN apt-get update -qq && apt-get install -y build-essential libpq-dev nodejs

RUN mkdir /rails_app

COPY Gemfile* /rails_app/

WORKDIR /rails_app

RUN ls

# RUN bundle install

# WORKDIR /

# RUN mkdir tmp/pids

# COPY . ./

# EXPOSE 3000

# CMD ["bundle", "exec", "puma", "-C", "config/puma.rb"]