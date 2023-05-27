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
  - username must be present and unique, min 3 max 25.
  - email address must be present and unique, max 105 \* email must be valid email format, check with email regex.
 
<img width="480" alt="image" src="https://github.com/Akash1298/alpha-blog/assets/65884746/6f7d23e9-f1ab-46ff-925d-29f55045e2cf">
<img width="480" alt="image" src="https://github.com/Akash1298/alpha-blog/assets/65884746/46fcc856-ed33-403a-ab84-2fec6758d4c5">
<img width="480" alt="image" src="https://github.com/Akash1298/alpha-blog/assets/65884746/6d3a8e74-af39-4d79-a7a1-a4f358050d3d">
<img width="480" alt="image" src="https://github.com/Akash1298/alpha-blog/assets/65884746/32608b7a-afd5-4b80-aedf-821f003d4d02">



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
