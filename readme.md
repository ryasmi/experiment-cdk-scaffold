# Template Experiment

1. Install the correct Node version with `nvm install`
1. Install dependencies with `npm ci`
1. Build the code with `npm run build`
1. Login into AWS > Select Account > Security credentials > Create access key
1. Configure AWS with `aws configure`
1. Bootstrap the CDK with `npm run bootstrap aws://{ACCOUNT_ID}/{REGION}`
1. Deploy the code with `npm run deploy`
1. You'll then get an endpoint to hit, just append `/api-demo` and open in your browser
1. It should say "hello"
