# Running the imported project

- Click **Run** to start the **Start application** workflow.
- The workflow runs `python3 server.py`, listening on `0.0.0.0:5000`.
- No third-party dependencies, secrets, or external service setup are required.
- The original `index.html` remains unchanged: visiting the page immediately
  redirects to `https://google.com`, preserving the URL fragment after `#`.
- External navigation may be blocked inside an embedded preview. Open the
  preview in a new browser tab to use the redirect.
- The server serves only `/` and `/index.html`; other paths return 404 so
  repository and configuration files are not exposed.
