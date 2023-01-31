# PER: https://pages.github.com/versions/ we need to use Jekyll 3.9.2
ARG JEKYLL_VERSION=3.9.2
ARG RUBY_VERSION=2.7
# Which needs Ruby 2.5.8
FROM ruby:${RUBY_VERSION}-alpine
# FROM jekyll/jekyll
# Add Jekyll dependencies to Alpine
RUN apk update \
&& apk add --no-cache build-base gcc cmake git \
# Update the Ruby bundler
&& gem update bundler

# RUN bundle install --quiet --clean
# CMD ["jekyll", "serve"]