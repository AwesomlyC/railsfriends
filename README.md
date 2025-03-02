# README

## Application for learning Ruby on Rails

## Technologies involved
- Ruby
- Ruby on Rails
- Bootstrap
- gemfile -> [devise](https://github.com/heartcombo/devise) (user authentication)
- Sublime Text
- Git Bash

### Requirements
- Ruby 3.3.7+
- Rails 8.0.1+

### MVC (Model-View-Controller)
- Model
  - How Rails handle databases i.e. where all schemas/database are located
- View
  - Handle the display for all frontend. What is displayed to the user
- Controller
  - Handle the "logic" and a want to retrieve data from the model to display content to the view.


### Partial
- Reusable component for webpages.
  - Common examples are navbar, footer, sidebar

### CRUD Scaffold
- rails g scaffold (database_name) (parameters --> first_name:string ...)
- How Rails create CRUD methods.

### [Associations](https://guides.rubyonrails.org/association_basics.html#types-of-associations)
- Way to associate database tables together (similar in RDBMS)
- belongs_to
- has_one
- has_many
- has_many :through
- has_one :through
- has_and_belongs_to_many

### Common Commands
- rails s (server)
- rails db:migrate
- rails g (generate) ...
- rails g scaffold

### Tutorial Credits
- [Learn Ruby on Rails - Full Course](https://www.youtube.com/watch?v=fmyvWz5TUWg)