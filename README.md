# Phone Clock Page

This folder contains a static mobile clock-in/out page for embedding in Google Sites.

## Use with Google Sites

1. Host this folder from an HTTPS-capable static host.
2. In Google Sites, choose **Embed** and paste the hosted `index.html` URL.
3. Open **Connection settings** on the page and enter the public HTTPS URL of the Timesheet API.
4. The API must be reachable by the phones and have CORS enabled for the hosted page origin.

For local testing, serve this folder with any static web server and point the page at the API address, for example `http://192.168.1.25:5099`.

The current prototype uses employee selection rather than authentication. Add employee PIN/login and restrict CORS before using it outside a trusted network.
