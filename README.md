# Installation
```bash
# Bundle version 2.2.3
# Rails version 6.1.6
# Ruby version 3.0.0
#
bundle install

rails db:create

rails db:migrate

brew install anycable-go

```

# Start

```bash
# server
bundle exec rails s --port 3000 -b 0.0.0.0
# anycable
bundle exec anycable
# ws
anycable-go --port=8080

# If you are using foreman
foreman start

```

