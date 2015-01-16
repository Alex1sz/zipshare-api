# Zipshare API
The Zipshare API is a RESTful API for the [ZipShare hosting and sharing
service](https://github.com/zipshare/zipshare). The API allows integrations of
ZipShare functionality into browsers, mobile apps, and command line tools.
Features are built into the API before being added into the web or command line
clients.

## Getting started
Install all the [dependencies](#dependencies), then run:

```shell-session
$ make setup  # Install gems and setup the database.
$ make run    # Runs the API locally
$ make test   # Runs all the tests
$ make docs   # Generates API and code documentation
```

## Contributing
Our [contribution guidelines](CONTRIBUTING.md) are summarized as:
* Work on whatever you think fits within the vision of Zipshare
* Create issues when you think of an enhancement or find a bug. Submit patches when
  you can.
* [CodeUnion owns all the code and related assets](LICENSE).
* [Be compassionate and kind to one another.](CONTRIBUTING.md#code-of-conduct)
  Harassment or verbal abuse of any kind is not tolerated.

## Dependencies
* Ruby 2.2
* Bundler
* make
* Postgresql
