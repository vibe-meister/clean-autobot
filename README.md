Shine Sprint 405 Cleaning Service Web App

Overview

This Google Apps Script web app powers a booking and inquiry system for Shine Sprint 405, a professional cleaning service specializing in move-in/move-out apartment cleanings, dorm cleanings, and recurring office cleaning. Deployed at https://script.google.com/macros/s/AKfycbyhvxS8JCDjzbPlUHo8k1soCKO2F9euA35BiFc4DorhYM0IjCb305sQevzUHwz06wNhDQ/exec, it handles client requests and responses.

Functionality





GET Requests: Returns a JSON response with service details or booking form.



POST Requests: Processes booking inquiries or client data submissions.



Access: Configured for "Anyone" or "Anyone, even anonymous" access, depending on deployment settings.

Usage





Access the /exec endpoint directly for JSON responses or via a client-side interface (e.g., HTML form).



Ensure requests use Content-Type: text/plain and redirect: follow to avoid CORS issues on mobile browsers.

Notes





Deployed with Google Apps Script; requires active deployment in the Apps Script editor.



Logs requests in the Executions tab for debugging.



Contact [Your Email] for support or to report issues.
