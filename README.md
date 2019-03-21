# README

Configuration:

* Ruby version: 2.5.0

* Rails version: 5.2.0

* Bundler version: 1.17.3

* Redis

Run below commands for testing:

```ruby
rails console
ActionCable.server.broadcast "web_notifications_channel", message: "<h1>Hello</h1>"
```
