# Linktree clone

This is a simple linktree clone. A user can see a list of a user's social media and links all on one page, along with a profile pic and simple blurb. Users can navigate to admin page to login and edit their profile

## Tech Stack

* Ruby 3.2.2 on Rails 7.0

* PG db

* Tailwind CSS  + heroicon icons

* Simple Form + simple_form_tailwind_css

* RSpec + Capybara testing with factory_bot


### To run locally:
```
git clone https://github.com/laurieroy/rails-linktree-clone
```

cd to dir, e.g. ```cd rails-linktree-clone```

Run bundle to install dependencies
```bundle ```

To create your database, run:
```
bin/rails db:create
```
<!-- ```bin/rails db:setup``` -->

To run the app locally:
```
bin/dev
```

Browse to localhost:3000

## To run all unit tests
```
rspec
```

<!-- system tests: -->