Firebase Service Account

    Navigate to the Left Sidebar and click on “Settings.”
    Choose “Users and Permissions.”
    Navigate to the “Service Accounts” tab.
    Choose Node.js, which should be the default option.
    Click “Generate New Private Key.”
    Click “Generate Key” on the popup. A JSON file should have downloaded to your computer.
    Rename the file to serviceAccount.json. We will need this file when we import.

serviceAccount.json

{
  "type": "service_account",
  "project_id": "PROJECT_ID_HERE",
  "private_key_id": "PRIVATE_ID_KEY_HERE",
  "private_key": "PRIVATE_KEY_HERE",
  "client_email": "CLIENT_EMAIL_HERE",
  "client_id": "CLIENT_ID_HERE",
  "auth_uri": "AUTH_URI_HERE",
  "token_uri": "TOKEN_URI_HERE",
  "auth_provider_x509_cert_url": "https://www.googleapis.com/oauth2/v1/certs",
  "client_x509_cert_url": "CLIENT_CERT_URL_HERE"
}