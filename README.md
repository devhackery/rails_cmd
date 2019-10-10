# Rails CMD



* Generate
```bash
rails new myapp -d mysql -T
rails new myapp --database=postgresql 
rails generate controller foobar --skip-assets
rails generate controller "api/v1/$1" --no_helper --no_assets
rails generate controller foo bar --skip-template-engine
rails g model YourModel --migration=false

```

* Running 

```bash
$ rails server -b 0.0.0.0
$ rails s -e production -d
$ redis-server
$ sidekiq
$ bundle exec sidekiq -C config/sidekiq.yml
$ bundle exec sidekiq -d -L log/sidekiq.log -C config/sidekiq.yml -e production
$ rubycritic    # provide a quality report of your Ruby code.
```

* Migration

```bash
$ rails db:create 
$ rails db:setup
$ rake db:migrate
$ rake db:rollback STEP=1 
$ rake db:migrate:down VERSION=20100905201547
```


* Pandit
```bash
$ rails g pundit:policy post
```

* Serializers
```bash
$ rails g serializer post
```

* Puma
```bash

```

* Capistrano

```bash
$ rails g serializer post
```

* Rubocop
```bash
```




* Other
```bash
 bundle update
 ```









 


