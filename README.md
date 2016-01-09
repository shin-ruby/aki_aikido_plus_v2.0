== README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database production dump

```bash
pg_dump -U aki_aikido_prod -d aki_aikido_prod -f ~/aki_aikido_prod.sql
```

* Database initialization in development

```bash
scp Shin@139.196.194.106:aki_aikido_prod.sql .
# replace aki_aikido_prod to aki_aikido_dev in that file
psql
drop database aki_aikido_dev;
drop user aki_aikido_dev;
create user aki_aikido_dev with CREATEDB password 'only_need_in_windows';
create database aki_aikido_dev;
\q
psql -U aki_aikido_dev aki_aikido_dev < aki_aikido_prod.sql
```

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


Please feel free to use a different markup language if you do not plan to run
<tt>rake doc:app</tt>.
