FROM ruby:2.6.0

RUN bundle config --global frozen 1

WORKDIR /usr/src/app

COPY ./rails-example-project-master/ .

RUN bundle install 
#RUN rails db:migrate

EXPOSE 3000

