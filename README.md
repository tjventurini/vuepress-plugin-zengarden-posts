# VuePress Plugin Zengarden Posts

Enables you to filter for the posts of your blog and expose it as `this.$posts` in Vue.

## Installation

```bash
npm i --save-dev vuepress-plugin-zengarden-posts
# or 
yarn add -D vuepress-plugins-zengarden-posts
```

## Usage

Add the following to your `config.js` or `index.js`.

```javascript
['zengarden-posts'],
```

Now you can access your posts through `this.$posts` in the frontend.

## Configuration

If you have your posts somewhere else then the default `posts` directory, then you need to add some configuration.

```javascript
['zengarden-posts', {
    path: '/articles/'
}]
```

