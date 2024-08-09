# blog_demo

## Description

This is a blog application built with Ruby on Rails. It allows users to create, read, update, and delete posts.

## Ruby Version

Ruby 3.3.4

## Rails Version

Rails 7.1.3.4

## System Dependencies

- Ruby 3.3.4
- Rails 7.1.3.4

## Configuration

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Javierdigital85/blog-rubyOnRails


   ```

2. **Navigate to the project directory:**

   ```bash
   cd blog-rubyOnRails
   ```

3. **Install dependencies:**

   ```bash
   bundle install
   ```

4. **Set up the database:**

   ```bash
   rails db:create
   rails db:migrate
   ```

## Usage

1. **Start the Rails server:**

   ```bash
   rails server
   ```

2. **Navigate to** [http://localhost:3000](http://localhost:3000) **in your browser.**

## Development

1. **To create a new post from the Rails console:**

   ```bash
   rails console
   ```

2. **Create a new post:**

   ```ruby
   Post.create(title: "My first post from Argentina", body: "This is the body of the post.")
   ```
