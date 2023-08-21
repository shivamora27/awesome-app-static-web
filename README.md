# awesome-app

> A reader for Awesome

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).




# Usage

You have the following environment variables which allow you to configure the
coming soon page:

| Variable name | Description                           | Example                                                                |
|-----------------|-------------------------------------------|---------------------------------------------------------------------------------|
| TITLE         | Webpage head title                   | TITLE="Awesome App"                                                    |
| PRODUCT_NAME  | Product name show on the page        | PRODUCT_NAME="My Awesome App"                                          |
| CATCHY_PHRASE | The sentence under the product name  | CATCHY_PHRASE="Awesome App is what you were looking for since a while." |
| FACEBOOK_URL  | Facebook button URL to your page     | FACEBOOK_URL="https://www.facebook.com/awesomeapp"                     |
| TWITTER_URL   | Twitter button URL to your page      | TWITTER_URL="https://www.twitter.com/awesomeapp"                       |
| GITHUB_URL    | Github button URL to your page       | GITHUB_URL="https://www.github.com/awesomeapp"                         |
| EMAIL         | Email to be used for the Email button | EMAIL="me@mydomain.com"                                                |

Run the image with the following:

```bash
docker run --name coming-soon -d -p 80:80 -e TITLE="Awesome App" -e PRODUCT_NAME="My Awesome App" zedtux/docker-coming-soon
```

Now you should be able to access it.



## License

  [MIT](LICENSE)




