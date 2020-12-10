## Node Slack API Starter 

Boilerplate code for a Slack app in Node using the [@slack/events-api](https://slack.dev/node-slack-sdk/events-api) package.

### Local Usage
* Create a [Slack app](https://api.slack.com/apps/new) if you don't already have one, or select an existing app you've created. 
* Once your app has been created find your app's signing secret.
* Create a .env file in your project's root directory and add your signing secret as follows: `SLACK_SIGNING_SECRET=[paste_your_secret_here]`
* run `npm install`
* run `npm run dev`