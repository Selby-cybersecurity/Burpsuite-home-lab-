## Burp Suite – Initial Testing

- Successfully installed and launched Burp Suite on Linux
- Encountered issues configuring the Burp CA certificate in the browser (TLS interception not fully enabled yet)
- Despite CA limitations, was able to:
  - Capture traffic via HTTP History
  - Target and analyze a self-built test website
  - Inspect GET requests and responses
  - Modify response values directly in the HTTP History tab to observe client-side behavior

## Notes
- Certificate trust remains the main blocker for full HTTPS interception
- Basic request/response manipulation confirmed working

## Next Steps
- Properly install and trust Burp CA certificate in Firefox
- Enable full HTTPS interception
- Begin structured testing (parameter tampering, session handling, auth logic)
