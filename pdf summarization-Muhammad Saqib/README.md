
## Instructions

1. Download or clone this project:
2. Install dependencies

```
$ npm install
```


### Environment setup

To run our example app, first we need to set up our environment variable, we can do this by:

- Get an OctoAI API token by following [these instructions](https://octo.ai/docs/getting-started/how-to-create-octoai-api-token/).
- Paste your API token in the file called `.env` in this directory.

```bash
OCTO_CLIENT_TOKEN=<your key here>
```

### Running the application

Run `dev` script to fire up server.
```bash
npm run dev

### Uploading PDF file
Upload a PDF file using the Upload button, and see both the current pdf text on the left, and the summarized version on the right.
