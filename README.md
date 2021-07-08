GH Pages for Workshop Content 

=================================

# Local Development

Resources: https://pages.github.com/


## 1. Installing Pre-reqs

https://jekyllrb.com/docs/installation/

## 2. Installing the bundler

`gem install jekyll bundler`

## 3. Install the Bundle from Gemfile

`bundle`

## 4. Serving the Site

`bundle exec jekyll serve`


# Editing Content

To add content as pages, you have to focus on 2 regions of the codebase.

1. `_data/navigation.yml`
  - This file serves as the list of the hierarchy of pages to show for the content to be rendered. You will see each of these routes appear in the sidebar on population. You can reference individual features like links within the pages themselves

2. `pages/**/*`
  - This directory contains all pages that can be rendered. They are references from the above `yml` file and where the content you want to create will end up. You can create new `.md` files and reference them as needed in the `yml` file described above. 

# Pushing to the website (Public)

1. `git add .`
2. `git commit -m "message"`
3. `git push`

After some time, you can see the rendered site at: https://merritt-brian.github.io/Workshop-Content-JHU