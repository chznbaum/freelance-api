# Freelance API

Make your freelancing more efficient by managing leads, proposals, project documents, clients and more.

*This is a work in progress.*

## Getting Started

### Prerequisites

#### Ruby ~> 2.4

Download and manage via [rbenv](https://github.com/rbenv/rbenv) or RVM(https://rvm.io/)

#### Rails ~> 5.1

```bash
gem install rails -v '~> 5.1'
```

#### PostgreSQL ~> 9.6

Follow the [instructions for downloading PostgreSQL](https://www.postgresql.org/download/) based on your operating system, and be sure to [create a database user with privileges](https://wiki.postgresql.org/wiki/First_steps).

### Installing

Clone the repository:

```bash
git clone https://github.com/chznbaum/freelance-api.git
cd ./freelance-api
```

Install the gems:

```bash
bundle install
```

And set up the database:

```bash
rails db:create
rails db:migrate
```

Start the development server:

```bash
rails s
```

You can test this by making a GET request to `localhost:3000` using Postman or an alternative.

## Tests

### End to End Tests

TBA

### Coding Style Tests

TBA

## Deployment

TBA

## Built With

* [Rails](http://rubyonrails.org/) - Web Framework
* [rbenv](https://github.com/rbenv/rbenv) - Environment Managemet
* [Bundler](http://bundler.io/) - Dependency Management
* [Heroku](https://www.heroku.com/) - Deployment Platform
* [Travis CI](https://travis-ci.org/) - Continuous Integration

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on the code of conduct, and the process for submitting pull requests.

## Versioning

TBA

## Authors

* **Chazona Baum** - Initial work

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for more details.

## Acknowledgements
