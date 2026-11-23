MARKET KILLER ZONE — starter website

This is a mobile-friendly static dashboard preview. It does NOT connect to Deriv or place trades.

Next implementation steps:
1. Deploy this project to an HTTPS host (for example, Vercel).
2. Register an OAuth 2.0 application in the Deriv developer dashboard using the final HTTPS callback URL.
3. Implement OAuth Authorization Code + PKCE on the server. Verify state and exchange the code on the backend only.
4. Confirm the exact Deriv Trader contract types and symbols supported by the current API before implementing execution.
5. Keep trading disabled until demo tests and risk checks pass.

Never put a Deriv password, client secret, or access token in browser code or a public repository.
