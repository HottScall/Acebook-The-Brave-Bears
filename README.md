AceBook  Build StatusCoverage Status
Welcome - Team - Screenshots - Our Process - Quickstart - Testing
Welcome to Bearbook
Bearbook is an iteration of the Makers Acebook clone engineering project. To try it out visit at: http://acebook-the-brave-bears.herokuapp.com/

Team
Yadira Sanchez
Nandini Patel
Carly Jenkinson
Steven Hektor
Scott Hall
Oliver Cripps
Screenshots
Signup
Signup

Login
Login

Profile
Profile

Our Process
We agreed to follow several High Quality Processes during the 2-week development period. The Agile process was our main focus and we kept the documentation from our daily standups, retrospectives and 2-day sprints in our repository Wiki.

Deployed at: http://acebook-the-brave-bears.herokuapp.com/

The card wall is here: https://github.com/CarlyJ88/Acebook-The-Brave-Bears/projects/1

Project Wiki: https://github.com/CarlyJ88/Acebook-The-Brave-Bears/wiki

Quickstart
First, clone this repository. Then:

> bundle install
> bin/rails db:create
> bin/rails db:migrate

> bundle exec rspec # Run the tests to ensure it works
> bin/rails server # Start the server at localhost:3000
To clean the database, run the following command:

> bin/rails db:migrate:reset
Testing
RSpec
bundle exec rspec to run all the RSpec feature and unit tests

Rubocop
bundle (if not installed)
rubocop to run

Test Coverage with Simplecov
Coverage reports are generated every time RSpec tests are run. To view the results:
bundle (if not installed )
cd coverage
open index.html

How to contribute to this project
See CONTRIBUTING.md
