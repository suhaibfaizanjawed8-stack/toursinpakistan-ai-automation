ToursInPakistan — Travel Lead Automation Demo Site

WHAT THIS PACKAGE DOES
- Provides a polished public demo landing page for Vercel.
- Embeds and links to the Google Form already created in the assignment.
- The Google Form continues sending submissions to its connected Google Sheet.
- Clearly labels Make.com sales email and AI classification as NOT YET IMPLEMENTED.

IMPORTANT
- This file does not deploy Google Forms, Google Sheets, or Make.com to Vercel; it only provides a public-facing demo page.
- Do not enter real customer information. Use fictional enquiries only.
- Keep the response spreadsheet private; do NOT set it to anyone with the link.
- Test data containing real personal numbers should be deleted from the Google Form response history and associated Google Sheet.

HOW TO DEPLOY
1. Open https://vercel.com/drop in your browser.
2. Sign in to a Vercel account.
3. Drag the file ToursInPakistan-Vercel-Demo.zip or select it using the upload control.
4. Select your team and enter a project name, such as toursinpakistan-lead-demo.
5. Select Deploy.
6. Open the generated *.vercel.app URL and verify the form works.

TO UPDATE THE GOOGLE FORM LINK
Edit index.html and replace both occurrences of:
https://docs.google.com/forms/d/e/1FAIpQLSeSSkdZaNy2KIFq1J_q4Lp_UbjNsTLpKdUXbD48mNYm_BCO1A/viewform
with the new responder URL.

NEXT ASSIGNMENT MILESTONES
- Day 2: Submit 5 fictional test enquiries and check all rows in Google Sheets.
- Day 3: Make.com Google Sheets trigger -> email notification.
- Day 4: Manual/optional API lead classification (Hot/Warm/Cold) and draft response.
- Day 5: End-to-end demonstration and report.
