# README

List of Ingredients
This repo serves as a companion to the tutorial A Rock Solid, Modern Web Stack—Rails 5 API + ActiveAdmin + Create React App on Heroku.

A screenshot of the app in action

Getting started
git clone https://github.com/heroku/list-of-ingredients.git
cd list-of-ingredients
bundle
yarn --cwd client install
bin/rake db:migrate db:seed start
Once you're ready to deploy to Heroku, run:

heroku apps:create
heroku buildpacks:add heroku/nodejs --index 1
heroku buildpacks:add heroku/ruby --index 2
git push heroku master
heroku run rake db:seed
heroku open
Or you can click this button to deploy straight to Heroku from this repository:

Deploy

Success!

Suggestions, problems, typos?
Get in touch by adding an issue.
