# Credentials format

## Algorithmia

File: `algorithmia.json`

```
{
  "apiKey": "sim8As72h56j3mBYqEOSHfLE4k81"
}
```

## Watson Natural Language Understanding

File: `watson-nlu.json`

```
{
  "apikey": "Qynm-JBOd9m7JqEAFSvSt4feydYO4Pt0xYvAfaNEY2LW",
  "iam_apikey_description": "Auto generated apikey during resource-key operation for Instance - crn:v1:bluemix:public:natural-language-understanding:us-south:a/ffcb2c250e19bc335de2e9f1533711c8:4423b565-1e77-4d4c-a56e-656b3af7ac0d::",
  "iam_apikey_name": "auto-generated-apikey-27b6655f-6a69-40ba-a46a-60ae25b6d10a",
  "iam_role_crn": "crn:v1:bluemix:public:iam::::serviceRole:Manager",
  "iam_serviceid_crn": "crn:v1:bluemix:public:iam-identity::a/ffcb2c250e19bc335de2e9f1533711c8::serviceid:ServiceId-3b990ca3-62e6-4445-b303-84239f956d01",
  "url": "https://gateway.watsonplatform.net/natural-language-understanding/api"
}
```

## Google Cloud Platform

File: `google-search.json`

```
{
  "apiKey": "sim8As72h56j3mBYqEOSHfLE4k81",
  "searchEngineId": "000698257139961718300:qdhm8xqmtxa"
}
```

File: `google-youtube.json`

```
{
  "web": {
    "client_id":"000698257139961718300.apps.googleusercontent.com",
    "project_id":"video-maker-000698257139961718300",
    "auth_uri":"https://accounts.google.com/o/oauth2/auth",
    "token_uri":"https://oauth2.googleapis.com/token",
    "auth_provider_x509_cert_url":"https://www.googleapis.com/oauth2/v1/certs",
    "client_secret":"000698257139961718300",
    "redirect_uris":["http://localhost:5000/oauth2callback"],
    "javascript_origins":["http://localhost:5000"]
  }
}
```