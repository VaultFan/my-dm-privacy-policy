ChatGPT said:
Privacy Policy for World Control API (“dispatch” endpoint)

Last updated: July 20, 2025

1. Data We Collect

Request Data: When you call the dispatch endpoint, we receive the JSON payload you send, including:

name (the operation name, e.g. get_npc_state, etc.)

arguments (the parameters for that operation, such as NPC objects or region details)

Metadata: We automatically log standard HTTP metadata (timestamp, request IP, User‑Agent header) for monitoring and debugging.

2. How We Use Your Data

Functionality: We use the data you provide in the JSON payload only to compute and return the requested result (e.g. NPC state, newly created region).

Logging & Debugging: We retain request logs for up to 30 days to diagnose errors, monitor performance, and detect abuse.

No Analytics or Profiling: We do not use your payload data for analytics, profiling, or any purpose beyond directly fulfilling your request or maintaining service health.

3. Data Retention

Persistent Storage: Any new or updated world‑state data (regions, locations, NPC moves) is written to your world_schema.yaml file; this file is entirely under your control.

Log Retention: Request logs are stored for 30 days, then purged automatically.

4. Data Sharing

Third‑Party Services: Your payload and logs are accessible to Replit (hosting provider) under their privacy policy. We do not share your data with any other third parties.

No Public Disclosure: We do not make any request or log data publicly accessible.

5. Security

All communication to the API occurs over HTTPS.

No authentication is required for the endpoint; access control is governed by obscurity of the URL. You are responsible for keeping your endpoint URL confidential to prevent unauthorized access.

6. Your Choices

Data Deletion: You can delete or modify your world data at any time by editing or replacing the world_schema.yaml file in your Replit project.

Log Clearance: To purge request logs sooner than 30 days, you may restart or stop your Repl; logs will be cleared when the service is redeployed.

7. Changes to This Policy
We may update this privacy policy to reflect service changes. The “Last updated” date at the top will indicate when any changes occur. Continued use of the API after updates constitutes acceptance of the revised policy.

# my-dm-privacy-policy
