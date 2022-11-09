#  FindFix Training - Find and fix common security defects in a  Node.js applications

## How to Set Up Your Copy of NodeGoat

### Run NodeGoat on Docker

The repo includes the Dockerfile and docker-compose.yml necessary to set up the app and db instance, then connect them together.

1) Install [docker](https://docs.docker.com/installation/) and [docker compose](https://docs.docker.com/compose/install/) 

2) Clone the github repository:
   ```
   git clone https://github.com/BoringAppsec/FindFixTraining
   ```

3) Go to the directory:
   ```
   cd FindFixTraining
   ```

4) Build the images:
   ```
   docker-compose build
   ```

5) Run the app
   ```
   docker-compose up
   ```
6) Navigate to http://localhost:4000

7) The database comes pre-populated with these user accounts created as part of the seed data -
* Admin Account - u:admin p:Admin_123
* User Accounts (u:user1 p:User1_123), (u:user2 p:User2_123)
* New users can also be added using the sign-up page.

## Supports

- This repo is powered by OWASP NodeGoat. We forked the repo and made chages as per our need. Thanks to OWASP for publishing awesome online resources, including NodeGoat
- Thanks to JetBrains for providing licenses to fantastic [WebStorm IDE](https://www.jetbrains.com/webstorm/) to build this project.

## License

Code licensed under the [Apache License v2.0.](http://www.apache.org/licenses/LICENSE-2.0)
