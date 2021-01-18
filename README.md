# rails-scaffold

## Environment

- ruby 2.7.2p137
- Rails 5.2.1
- PostgreSQL 10.15

## Installation

```shell
$ bundle install
```

## Run

Launch the database server.

```shell
$ brew services start postgresql@10
```

Launch the rails server.

```shell
# $ bundle exec rails s
$ bin/rails -s
```

## Stop

```shell
$ brew services stop postgresql@10
```

## Debug

```shell
$ psql postgres
```
