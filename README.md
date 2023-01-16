# My Links

Inspired by Linktree and others, but you should be able to control your page for free. Just getting started and will add more notes soon. 

## About this project

This is free for you to fork, reuse, update this template, etc. First you will need to clone and install the dependencies. This is built using [NodeJS](https://nodejs.org/en/) and [11ty](https://www.11ty.dev/).

```sh
$ git clone git@github.com:cjerrington/MyLinks.git
$ cd MyLinks
$ npm run install
```

### Commands

These commands assume you're in a unix environment, but they should work anywhere `npx`/`npm` is available.

### Develop

To test the site locally you can serve the pages. As you make changes to your template your browser will auto reload as well. 

```sh
$ npx @11ty/eleventy --serve
```

### Build

Once happy with your links, you can build you site, and then upload the `_site` directory to your hosting. 

```sh
$ npx @11ty/eleventy
```

## Adding your content

1. Update your site settings in the `_data/site.json` file 
2. Update your links in the `_data/links.json` file. 

For the links, you can adjust the style based on the [bulma](https://bulma.io/documentation/elements/button/) styling classes

```json
{
    "name": "Website",
    "href": "https://claytonerrington.com",
    "style": "is-success" 
  }
```

## Road Map

1. Look into building with GitHub Actions and deploy
2. Look into building with Netlify and deploy
3. Update CSS to use SASS with Bulma to create themes
4. Bring CSS back local 
5. Update `site.json` with page coloring and other preferences. 

## Contributing

Any and all contributions are welcome! This is a simple project for me to help others out and get introduced to [11ty](https://www.11ty.dev/) (eleventy) for something and different from Jekyll. 