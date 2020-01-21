# Reason React Playground

This is an example to show [Reason-React](https://reasonml.github.io/reason-react/) hosted with AWS Amplify.

This is just the normal `create-react-app` template, but rewritten in reason.

`.re` files are converted to `.js` files via `bsb make-world` and then packaged into the `build` folder using `react-scripts build`.

AWS Amplify is just calling `npm run build` and therefore `package.json` calls the above.

[Hosted here](http://reason-playground-20200121115054-hostingbucket-master.s3-website-eu-west-1.amazonaws.com/)
