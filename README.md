
## Initial settings to run the project

```bash

# install Ruby on Rails dependencies
bundle install

# install Node dependencies
yarn install
yarn install --ignore-engines


# create the development and test databases
rails db:create

# create the tables
rails db:migrate

# populate data
rails db:seed

# run the project
rails s
```

### Prerequisites

- Ruby on Rails v6.x. To learn how to install Ruby on Rails, please follow this [link](https://guides.rubyonrails.org/getting_started.html)

### Usage

- start a server with `rails s`

- open `http://localhost:3000/` in your browser.

- Sign up with your email and password, an email confirmation will be sent to you and then you can start enjoying the app...

- After seeding there will be 10 users created and the user1 and user10 are admins, the rest are all normal users, you can find the user details bellow, all users have the same password for testing purposes.
- Admins:
  - user1@email.com | password: 123456
  - user10@email.com | password: 123456
- Normal users:
  - user2@email.com | password: 123456
  - user3@email.com | password: 123456

