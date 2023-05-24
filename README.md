## Alpha-Blog

Steps are necessary to get the application up and running.

- Ruby version: "3.1.3"

- Rails version: "~> 7.0.4", ">= 7.0.4.3"

- Database creation

```
  rails db:create
```

- Database initialization

```
  rails db:migrate
```

- How to run the server

```
  rails server
```

## Resource

- Users - create users table and model - add validations
  - username must be present and unique, min 3 max 25
  - email address must be present and unique, max 105 \* email must be valid email format, check with email regex

Associations

- One-to-many
  between users and articles
- Many-to-many
  between articles and article-categories

REST for users

Authentication

- Login using secure password

Restriction of actions

- Based on logged in/logged out state

Security

- Admin user functionality and access level
