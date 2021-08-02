# Docs Editor Preview
This is a preview of [the Docusaurus Docs Editor Plugin](https://github.com/jlvandenhout/docusaurus-plugin-docs-editor).

[**LIVE PREVIEW**](https://jlvandenhout.github.io/docusaurus-plugin-docs-editor)

## Usage
To run the preview locally, you will need to set up a [GitHub OAuth App](https://docs.github.com/en/developers/apps/building-oauth-apps/creating-an-oauth-app) to let users authorize your app from `localhost` and a server that manages your Client Secret and allows users to swap their authorization code for an access token (have a look at [Gatekeeper](https://github.com/prose/gatekeeper) how to do that).

Then clone this repository and start the development server with the `CLIENT_ID` and `TOKEN_URL` environment variables set to the Client ID you received from GitHub and the URL to your authorization endpoint:

```
git clone https://github.com/jlvandenhout/docusaurus-plugin-docs-editor-preview.git
cd docusaurus-plugin-docs-editor-preview
CLIENT_ID=12345 TOKEN_URL=http://example.com yarn start
```
