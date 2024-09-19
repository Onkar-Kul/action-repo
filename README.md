# 🌐 Webhook Action
In this repository webhooks added that triggers some actions like push, pull which will
trigger webhook-repo api endpoints to store the actions data in mongodb

You can see the code in webhook-repo and the webhooks in this repo

## 🔧 Configure Webhook on GitHub
To receive GitHub events, you need to configure a Webhook on your GitHub repository:

1. Go to your GitHub repository settings.
2. Select Webhooks → Add Webhook.

3. Setup ngrok to sent the payload securely on your local machine

4. Set the Payload URL to http://your_ngork_address/webhook.
5. Choose application/json as the Content Type.
6. Select events to trigger the webhook (e.g., push, pull request, merge).
7. Add webhook 

