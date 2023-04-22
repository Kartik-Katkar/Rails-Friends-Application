## Gif 

<p align="center">
  <img src="./Screenshot/app.gif" alt="Image"/>
</p>

## Features

The website is a robust CRUD (Create, Read, Update, Delete) application developed using Ruby on Rails and integrated with popular gems like Devise. It is specifically designed for managing data related to friends.

Users can easily create new friends by adding their details such as name, contact information, and other relevant information. They can also view and search for existing friends, making it convenient to keep track of all friends in one place.

Updating and editing friends' information is made simple with the website. Users can easily modify their friends' details, such as phone numbers or email addresses, ensuring that the information is always up-to-date and accurate.

In addition, the website provides the ability to delete friends from the list if they are no longer needed, giving users the flexibility to manage their friends' data as per their preferences.

To ensure security, the website is integrated with Devise, a powerful authentication and authorization solution. This ensures that user accounts and friends' data are protected and secure. Users can sign up, sign in, and manage their account information with confidence.

The website is designed with a user-friendly interface, providing a seamless experience for managing friends' data. It leverages the power of Ruby on Rails and gems like Devise to create a reliable and efficient CRUD application for managing friends' data effectively.

##### Prerequisites


The setups steps expect following tools installed on the system.

- Ruby [2.7.7](https://www.ruby-lang.org/en/news/2022/11/24/ruby-2-7-7-released/)
- Rails [7.0.4.2](https://rubygems.org/gems/rails/versions/7.0.4)

Gem used - Devise [get gem](https://rubygems.org/gems/devise)

##### 1. Check out the repository

```bash
git clone git@github.com:Kartik-Katkar/Rails-Friends-Application.git
```

##### 2. Create database.yml file

Copy the sample database.yml file and edit the database configuration as required.

```bash
cp config/database.yml.sample config/database.yml
```

##### 3. Create and setup the database

Run the following commands to create and setup the database.

```ruby
bundle exec rake db:create
bundle exec rake db:setup
```

##### 4. Start the Rails server

You can start the rails server using the command given below.

```ruby
bundle exec rails s
```

And now you can visit the site with the URL http://localhost:3000

Objective - Learning Ruby on Rails with a Project
