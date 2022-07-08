git clone https://github.com/sh1raori/blogdock

cd blogdock/development

docker-compose run web bundle install

docker-compose run web rails db:reset

docker-compose build

docker-compose up
