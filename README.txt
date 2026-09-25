Canada Casting Studio – prototype

Open "Canada Casting Studio.dc.html" through a local web server (browsers block
loading the linked screen files when opened directly from disk).

Easiest ways:
  • Mac/Linux terminal, in this folder:   python3 -m http.server 8000
  • Windows (with Python):               py -m http.server 8000
  • Or with Node:                         npx serve .
Then visit:  http://localhost:8000/Canada%20Casting%20Studio.dc.html

VS Code users: right-click the file → "Open with Live Server".

Files
  Canada Casting Studio.dc.html  – main prototype (state, routing, variant switcher)
  CCS Public.dc.html             – landing A/B/C, sign up, log in, register as, terms, resume
  CCS Onboarding.dc.html         – onboarding layouts A/B/C
  CCS Step.dc.html               – step fields, uploads, verification, review
  CCS Checkout.dc.html           – payment, submitted, verification, activated
  CCS App.dc.html                – home, registrations, casting calls, messages
  assets/                        – logo mark and poster image
  support.js                     – runtime
