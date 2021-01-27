# README
updated 2020 01 26
This repo includes the same code for a standard installation of spree
see :
https://github.com/spree/spree
installed samples
bundle exec rails db:seed
bundle exec rake spree_sample:load
bundle exec rails g spree:frontend:copy_storefront

also locally installed imagemagick with brew
and gem minimagick

WITH THE EXCEPTION of database production is MSQL
config info located as expected in database.yml
