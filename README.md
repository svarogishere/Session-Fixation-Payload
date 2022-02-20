# Session-Fixation-Payload
Simple payload to fixate session or cookie for victim account.

Confirm Session Fixation Vulnerability:
1) Logout from your account and confirm that session/cookie is still present.
2) Copy session cookie.
3) Trick the authenticated user to open XSS link and set your session instead of his.
4) Refresh your page (incognito/private) and see that you are logged in as victim.
