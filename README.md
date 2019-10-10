# Rails CMD



1.Generate CMD

```bash
rails server -b 0.0.0.0
rails s -e production

rails new bookRegistry -T
 rails new bees -d mysql
rails new myapp --database=postgresql
rake db:create 
rails db:setup
```



 bundle update


 rails d scaffold apiClientApplication name:string client_id:string client_secret:string grant_type:string code:string redirect_uri:string site:string authorize_url:string token_url:string


rake db:migrate

rake db:rollback STEP=1 
rake db:migrate:down VERSION=20100905201547


rails generate controller foobar --skip-assets

rails generate controller "api/v1/$1" --no_helper --no_assets

rails generate controller foo bar --skip-template-engine


rails g model YourModel --migration=false


redis-server
sidekiq

 bundle exec sidekiq -C config/sidekiq.yml

bundle exec sidekiq -d -L log/sidekiq.log -C config/sidekiq.yml -e production

 






(N+1 queries),
 gem 'bullet' 

  gem "rubycritic", require: false

cmd $ rubycritic    # provide a quality report of your Ruby code.
