# Events engine for Refinery CMS.

## How to build this engine as a gem

    cd vendor/engines/events
    gem build refinerycms-events.gempspec
    gem install refinerycms-events.gem
    
    # Sign up for a http://rubygems.org/ account and publish the gem
    gem push refinerycms-events.gem
    
## TODO: 

* Add RSS feed
* Add sharing interface
* Add "disabled" next / prev buttons
* Add comment spam protection
* Add comment moderation in ADMIN section
* Add "reply" form & logic for comment replies
