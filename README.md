### pliny
---

https://github.com/interagent/pliny

https://github.com/interagent/pliny/wiki

```
gem install pliny
pliny-new myapp
cd myapp && bin/setup

bundle exec pliny-generate modl artist
bundle exec plicy-generate mediator artists/creator
bundle exec pliny-generate endpoint artists
bundle exec pliny-generate migration fix_something
bundle exec plicy-generate schema artists

bundle exec rake
bundle exec rspec spec/acceptance/artists_spec.rb
bundle exec pliny-generate

pliny-generate endpoint NAME
pliny-generate help [CMD]
pliny-generate mediator NAME
pliny-generate migration NAME
pliny-generate model NAME
pliny-generate scaffold NAME
pliny-generate schema NAME
pliny-generate serializer NAME

rake db:create
rake db:drop
rake db:migrate
rake db:rollback
rake db:schema::dump
rake db:schema::load
rake db:schame::merge
rake db:seed
rake db:setup
rake schema

foreman start
foreman run bin/console
foreman run bin/run 'puts "hello"'

bundle install
createdb pliny-gem-test
rake

```

```ruby
Sequel.migration do
  change do
    create_table(:todos) do
      uuid :id, default: Sequel.function(), primary_key: true
      timestamptz :created_at, default: Sequel.function(:now), null: false
      timestamptz :updated_at, default: Sequel.function(:now), null: false
    end
  end
end

```

```
```

