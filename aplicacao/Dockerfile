FROM ruby:3.0.0

RUN gem install bundler

WORKDIR /app
COPY . /app/

RUN bundle install

EXPOSE 3000