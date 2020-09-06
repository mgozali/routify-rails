# Svelte Routify

```
rails new routify-rails -B -T --webpacker=svelte --skip-turbolinks
rake db:create
rails g controller static index
yarn add -D @sveltech/routify

mkdir app/javascript/pages
echo "<h1>About</h1>" > app/javascript/pages/about.svelte

yarn routify -p app/javascript/pages -b
rails server
```
