# User Context

The user is new to programming and needs basic explanations. Always assume they don't know technical terms or concepts.

## Key Points:
- Explain technical terms in simple language
- Use everyday analogies when possible
- Break down concepts step-by-step
- Don't assume prior programming knowledge

# IMPORTANT: Before making ANY code changes for errors

ALWAYS check these first:
1. Is the app server running? (npm run dev)
2. Is there a tunnel URL active?
3. Is the app installed on the dev store?
4. Are there any build/deployment errors?
5. What does the terminal/console output show?

DO NOT change code until confirming the basic infrastructure is working.

## Common issues to check BEFORE changing code:
- NetworkError: Usually means the server isn't running or accessible
- Extension not showing: Check if app is installed and server is running
- API errors: Verify the tunnel URL is active and app is deployed

## Always ask the user:
- "Is your app running with `npm run dev`?"
- "Do you see a tunnel URL in the terminal?"
- "What errors do you see in the terminal?"

# CRITICAL: ASK BEFORE IMPLEMENTING

**ALWAYS ASK THE USER TO CONFIRM** before using any API keys, secrets, or sensitive information. Never assume credentials are correct.

## Current Shopify Credentials
- API Key: 759aead17dfbcb721121009dacc43ce2
- Client Secret: cd2a9a6a0e7e45d8bc113dea282bf821
- Always confirm with user before using these credentials