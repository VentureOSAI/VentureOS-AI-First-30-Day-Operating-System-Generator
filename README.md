# VentureOS AI — Live AI Execution Agent

A live, Claude-powered execution agent in the VentureOS AI venture-creation
pipeline. Produces a finished, ready-to-use deliverable from the user's inputs.

## Access tiers
- FREE (active): the user supplies their own Claude API key, stored only in
  their browser (localStorage) and sent directly to api.anthropic.com — never
  to any VentureOS server. Zero inference cost to VentureOS AI.
- Subscription (coming soon, inactive placeholder).
- One-time access (coming soon, inactive placeholder).

The agent calls the Claude API directly from the browser using the
anthropic-dangerous-direct-browser-access header and the model
claude-sonnet-4-6.

Built by VentureOS AI · ventureosai.com
Mohammad Bukkar | Economic Systems Architect & Founder

## Deployment
Static HTML — no build step, no server, no functions. Deploy via GitHub →
Netlify, publish directory ".".
