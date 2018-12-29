# StandardNotes & Docker

This repository contains all the configuration to generate the [StandardNotes](https://github.com/standardfile/ruby-server) Docker's image.

## Usage

- Build the image

```sh
docker build -t standardnotes .
```

- Run the stack

```sh
docker-compose up -d
```

- Run the database migrations

```sh
docker exec -it standardnotes_standardnotes_1 bundle exec rails db:create db:migrate
```

## License

**MIT**
