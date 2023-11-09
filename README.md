# automate-percy-wdio

[WebdriverIO](http://webdriver.io/) Integration with BrowserStack.

![BrowserStack Logo](https://d98b8t1nnulk5.cloudfront.net/production/images/layout/logo-header.png?1469004780)

<img src = "https://webdriver.io/img/webdriverio.png" height = "100">

## Setup
* Clone the repo
* Install dependencies `npm install`
* You can setup environment variables for all sample repos (see Notes) or update `*.conf.js` files inside the `conf/` directory with your [BrowserStack Username and Access Key](https://www.browserstack.com/accounts/settings)
* Create a [Percy Automate Project](https://www.browserstack.com/docs/percy/get-started/create-project)
* Setup the [PERCY_TOKEN](https://www.browserstack.com/docs/percy/get-started/set-env-var) as the environment variable. 

## Running your tests
- To run parallel tests, run `npx percy exec -- npm run test`
- To run local test, run `npx percy exec -- npm run local`

## Additional Resources
* [Documentation for writing automate test scripts in Node](https://www.browserstack.com/automate/node)
* [Customizing your tests on BrowserStack](https://www.browserstack.com/automate/capabilities)
* [Browsers & mobile devices for selenium testing on BrowserStack](https://www.browserstack.com/list-of-browsers-and-platforms?product=automate)
* [Using REST API to access information about your tests via the command-line interface](https://www.browserstack.com/automate/rest-api)