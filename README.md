# Seb.Wiki - Local Development

Most of this project was based on: [Continuous Drupal: Maintaining a Drupal Website With Docker, Git & Composer](https://circleci.com/blog/continuous-drupal-p1-maintaining-with-docker-git-composer/)

## Objective

Have a Drupal 8 site relying on Docker and Composer, up and running, as soon as possible,

## Dependencies

Docker

Composer

Drupal 8 (current: 8.7.6)

MariaDB (10.3)

## Usage

Once everything is running: localhost:8080/

## Containers

[Drupal](https://hub.docker.com/_/drupal/)

[Maria DB](https://hub.docker.com/_/mariadb/)

## Others ressources

[drush-launcher](https://github.com/drush-ops/drush-launcher)

## External ressources

_places I took code from, and adapted it for my needs_

(I was on a thight schedule to make a working site, so I couldn't afford to start those from scratch)

[Continuous Drupal: Maintaining a Drupal Website With Docker, Git & Composer](https://circleci.com/blog/continuous-drupal-p1-maintaining-with-docker-git-composer/)
[Continuous Drupal Part II: Drupal 8 CI](https://circleci.com/blog/continuous-drupal-p2-continuous-integration/)

## Future Plans

* Include continuous integration in the workflow
