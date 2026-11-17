# Meeting subdomain

Add this record in the DNS zone for ans-siti.com:

| Type | Host | Target | TTL |
| --- | --- | --- | --- |
| CNAME | meeting | pranilpatiltech-cloud.github.io | Default / Auto |

Keep existing @, www, email and other subdomain records unchanged. Resolve any conflicting record only for the meeting hostname.

GitHub Pages: Deploy from a branch > main > / (root).
Custom domain: meeting.ans-siti.com
After DNS verification and certificate issuance, enable Enforce HTTPS.

Opening the subdomain redirects automatically to https://meet.google.com/bua-oriv-xot. A fallback Open Google Meet button is provided. This opens the Meet landing screen; Google sign-in, host admission and joining remain controlled by Google Meet.

To change the meeting later, update the URL in index.html and 404.html (refresh tag, script and button).
