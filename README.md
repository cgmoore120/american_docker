# american_docker

# American Docker

This docker container allows for ruby to parse a Date using the american_date gem

## To build this image

Clone the repo: 
  git clone git@github.com:cgmoore120/american_docker.git

Then build the container from the root repo directory:
  docker build -t cgmoore120/american_date ./

## To run this image

This will be a one-and-done run that returns the american formatted date (month/day/year) parameter as year/month/day
  docker run cgmoore120/american_date ruby /american_date.rb '01-20-1982'

OR
  docker run cgmoore120/american_date ruby /american_date.rb '01 20 1982'
