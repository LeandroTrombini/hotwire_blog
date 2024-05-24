# README

## Turbo Frame Articles App

This is a simple Rails application designed to demonstrate the use of Turbo Frames. The application allows users to create, read, update, and delete articles.

### Features
User Authentication: Users can sign up, log in, and log out.
Article Management: Users can create, view, edit, and delete their own articles.

### Technologies

- Ruby on Rails: A server-side web application framework written in Ruby. It is a model–view–controller (MVC) framework, providing default structures for a database, a web service, and web pages.
- Turbo Frames: A part of the [Hotwire](https://hotwire.dev/) framework by Basecamp, Turbo Frames allow for partial page updates without the need for client-side JavaScript frameworks.

### Getting Started
To get started with the app, clone the repo and then install the needed gems:

```bash
bundle install
```

Next, migrate the database:

```bash
rails db:migrate
```

Run the app in a local server:

```bash
rails server
```

