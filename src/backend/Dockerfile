FROM ruby:3.3

WORKDIR /app

RUN apt-get update -qq && apt-get install -y nodejs npm default-mysql-client
RUN gem install rails -v 8.0.0

COPY . .