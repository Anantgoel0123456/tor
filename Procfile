setup:
  addons:
    - plan: heroku-postgresql
      as: db
build:
  docker:
    worker: Dockerfile
run:
    worker: bash start.sh
