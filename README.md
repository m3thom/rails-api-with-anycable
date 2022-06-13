# Installation
```bash
# Bundle version 2.2.3
# Rails version 6.1.6
# Ruby version 3.0.0
#
bundle install

rails db:create

rails db:migrate
```

# Start

```bash
# server
bundle exec rails s --port 3000
# anycable
bundle exec anycable
# ws
anycable-go --port=8080

```

