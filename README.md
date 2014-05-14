# blog

a [Sails](http://sailsjs.org) application

sails new blog --linker
sails generate model Article title:string content:string
sails generate controller Article index show new edit

...

Profit!

# business
authentication
slugs for urls

# controller
CRUD article
CRUD comment
override, and add redirects

# models
article
comment
page

# views
article: index, show, form, edit/new, partials (comment/article)
page: index, show, form, edit/new, partials
-- markdown editor

## prepare database for prod
add relevant database adaptor via npm
set options in connections.js
choose adaptor in models.js

# todo:
authorization for page editing
remove epic editor altogther
