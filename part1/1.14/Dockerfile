FROM ruby:2.6.0
RUN apt-get update && apt-get install -qq -y nodejs

WORKDIR /app
COPY rails-example-project /app
RUN bundle install
EXPOSE 3000

RUN rails db:migrate

CMD FRONT_URL=http://localhost:3010 rails s
