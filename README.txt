FRIENDS PARTY TICKET SITE — DEMO

FILES
- index.html: website demo
- friends-party-poster.jpg: event poster used on the homepage

TRY IT
1. Keep both files in the same folder.
2. Open index.html in a browser.
3. Create a member account, submit a test M-Pesa code, and check My Tickets.
4. Open Admin sign-in from the page using Alt+Shift+A.
   Demo admin: username admin / password Friends@2026
5. Admin can approve/reject submitted payment entries.

IMPORTANT LIMITATIONS
This is a front-end demo. It saves data in localStorage in one browser on one device.
It does NOT share bookings across different phones/computers, securely protect passwords,
send payment codes to an online admin, or connect to Safaricom/M-Pesa. Admin approvals
are only demo actions. Do not use it to collect real payments yet.

FOR A REAL PUBLIC WEBSITE
It needs a hosted backend/database (e.g. Supabase/Firebase), secure admin authentication,
server-side validation, HTTPS hosting, backups, and preferably a payment confirmation
process. Until then, verify every code against your actual Pochi/M-Pesa transaction record.
The event year is intentionally not set because it was not confirmed.
