# gatsby-starter-try-ghost 

A Gatsby starter for creating blogs from headless Ghost CMS. 

Turn your Ghost blog into a lightning fast static website. This Gatsby theme is a frontend replacement of the Ghost handlebars engine featuring the standard Ghost Casper 3 skin and functionality. All content is sourced from a headless Ghost CMS.


## Demo

Play with the [Demo](https://styxlab.github.io) to get a first impression.


## Features

- Ghost Casper skin and functionality
- Sticky navigation headers
- Hover on author avatar
- Secondary navigation
- Styled 404 page
- SEO optimized
- Fully responsive
- Composable and extensible

## Getting Started

1. Install this starter by running

    ```bash
    gatsby new try-ghost https://github.com/styxlab/gatsby-starter-try-ghost
    ```

2. Change directory

    ```bash
    cd try-ghost
    ```

3. Run

    ```bash
    gatsby develop
    ```
    and visit your site at `http://localhost:8000`.

## Configure `siteConfig.js`

Update at least `siteUrl`.


## Configure the Ghost content API keys in file `.ghost.json`

If you want to source content from your own Ghost CMS, you need to change the keys to match yours:

    ```bash
    {
        "development": {
            "apiUrl": "http://localhost:2368",
            "contentApiKey": "9fccdb0e4ea5b572e2e5b92942"
        },
        "production": {
            "apiUrl": "http://localhost:2368",
            "contentApiKey": "9fccdb0e4ea5b572e2e5b92942"
        }
    }
    ```


# Copyright & License

Copyright (c) 2020 styxlab - Released under the [MIT license](LICENSE).
