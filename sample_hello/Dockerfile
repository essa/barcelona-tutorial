
FROM ruby:slim

RUN mkdir /app
WORKDIR /app
ADD Gemfile /app
ADD Gemfile.lock /app
ADD hello.rb /app
RUN bundle
