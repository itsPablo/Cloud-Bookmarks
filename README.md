# Cloud Bookmarks

Feel free to deploy this app to your AWS Account, for use with your own domain name. This [document](https://docs.aws.amazon.com/amplify/latest/userguide/custom-domains.html) details how to add a custom domain to Amplify Console.

[![amplifybutton](https://oneclick.amplifyapp.com/button.svg)](https://console.aws.amazon.com/amplify/home#/deploy?repo=https://github.com/donPatino/Cloud-Bookmarks)

When using the above button the build fails because `src/aws-exports.js` is not published to the repo. I found that it is easier to use `amplify init --app https://github.com/donPatino/Cloud-Bookmarks` as detailed in this [document](https://aws.amazon.com/blogs/mobile/amplify-cli-adds-scaffolding-support-for-amplify-apps-and-authoring-plugins/) because a new `src/aws-exports.js` is created.


## AWS Services Used

- [Amplify Console](https://aws.amazon.com/amplify/console/)
- [AppSync](https://aws.amazon.com/appsync/)
- [DynamoDB](https://aws.amazon.com/dynamodb/)



## JavaScript

- [Amplify Framework](https://aws.amazon.com/amplify/framework/)
  - [DataStore](https://docs.amplify.aws/lib/datastore/getting-started/q/platform/js)
  - [Authentication](https://docs.amplify.aws/lib/auth/getting-started/q/platform/js)
  - [React Components](https://docs.amplify.aws/ui/q/framework/react)
- [React](https://reactjs.org/)
- [React-Router](https://reactrouter.com/)
- [Materials UI](https://material-ui.com/)
- [Formik](https://formik.org/)

Please create an issue for any suggestions or issues.