Setting up the Environment
--------------------
Currently working with Ruby 2.3.1

1. gem install bundle
1. bundle update

Development
--------------------
bundle exec awestruct -d --force

Deploying to Production
-----------------------
bundle exec awestruct -P production --deploy --force --generate
