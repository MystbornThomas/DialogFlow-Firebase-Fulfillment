# DialogFlow-Firebase-Fulfillment
Upgraded starting place for firebase fulfillment for dialogflow

## Instructions
- Goto dialogflow - create your agent
  - Under Agent settings, click Export/Import tab
  - Restore From Zip & Select the .zip in ./DialogflowData 
  - Copy your project id from Settings->General ie introbot-jf438
  - Open Fulfillment tab
    - Enable Webhook Fulfillment
    - Paste this URL, but insert your project ID `https://us-central1-<YOUR_PROJECT_ID>.cloudfunctions.net/dialogflowFirebaseFulfillment`
- Install Firebase CLI - https://firebase.google.com/docs/cli/#setup
- Follow directions under "Deploy your function with the Firebase CLI"
- Goto your firebase console & open your project https://console.firebase.google.com
  - Click Databse-> Enable Cloud Firestore
- Test out the feedback feature & make sure the data appears in the Firestore database!
