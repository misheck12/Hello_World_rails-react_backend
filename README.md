# Hello-Rails
This is a simple project just to learn how to build an only api rails app.

## Built With

- Ruby on Rails
- PostgreSQL

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

- [Ruby](https://www.ruby-lang.org/en/)
- [Rails](https://gorails.com/)

### Setup

- Make sure you have Ruby on Rails set up properly on your computer
- Clone or download this repo on your machine
- Enter project directory

### Development Database

```sh
# Install dependencies
bundle install
# Create user
sudo -u postgres createuser -e ced00 -s
# Create the database
rake db:create
# Run database Migration
rails db:migrate
# Run the server
rails s
```

## Author

👤 **Cédric Kossi**

- GitHub: [@Misheck](https://github.com/mishec12)
- Twitter: [@Misheck](https://twitter.com/mishecklivingi2)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](./MIT.md) licensed.
