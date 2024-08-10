FROM ruby:3.2

RUN apt-get update -qq && \
    apt-get install -y nodejs postgresql-client \
    curl gnupg build-essential libssl-dev libreadline-dev zlib1g-dev

RUN gem install rails
    
WORKDIR /app

VOLUME [ "/app" ]
