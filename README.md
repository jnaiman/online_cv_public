# Online CV Templete for IS445

This is a resource for [IS445 as of Fall 2022](https://uiuc-ischool-dataviz.github.io/is445_bcubcg_fall2022/).  It is a way to host an online CV with interactive visualizations.  See the course page for more materials.

# How to use this repo

## Download & install

 1. clone this repo or download the contents
 1. make sure you have Ruby *properly* installed (see [the course's install instructions](https://uiuc-ischool-dataviz.github.io/is445_bcubcg_fall2022/week09/installation_instructions_week11.html) for this process)
 1. Install using `bundle install` (see [the course's install instructions](https://uiuc-ischool-dataviz.github.io/is445_bcubcg_fall2022/week09/installation_instructions_week11.html))
 1. Host locally with `bundle exec jekyll serve` or `bundle exec jekyll serve -l` (live reload)
 1. Modify files as needed (see sections below)

## General configurations

Edit info in: _config.yml

Some things you should be sure to check
 1. The "how to use this document" info at the top
 1. title, description, repository -- basic title and linking info
 1. baseurl -- in case you want to have it be a sub-page of your main github.io page
 1. exclude -- this section at the end of the config file, add at will in case you have other things stored in your github.io repo

## About page

Edit info in:
 1. pages/about.md for your general introduction
 1. _data/programming-skills.yml to update your your programming skills list
 1. _data/other-skills.yml to update other skills
 1. timeline.yml to update the timeline of your CV


## Sources

This is an amalgamation of [portfolYOU](https://github.com/YoussefRaafatNasry/portfolYOU) and [4dcu.be](https://github.com/4dcu-be/4dcu.be).

[portfolYOU](https://github.com/YoussefRaafatNasry/portfolYOU) was used for:
 * 

# ------------- Old ramblings below -------------

# Info for how this was created

1. Start by searching for Jeykll themes: https://github.com/topics/jekyll-theme
2. pick the following: https://github.com/YoussefRaafatNasry/portfolYOU
3. clone and follow the "Installation" instructions here: https://youssefraafatnasry.github.io/portfolYOU/docs/
4. Added port
5. remove Gemfile.lock if needed
trying to install with: bundle install --path ~/.gem
5. `bundle install` in directory 


bundle exec jekyll serve --> without the l for live reload if something else is running?

NOTE!!! it is quite likely that you have to serve the site locally and/or delete _site before pushing for your changes to go live.  I AM NOT SURE.  Have to re-start after you do a change to the config.yml file


