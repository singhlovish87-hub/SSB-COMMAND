SSB COMMAND — AUTHENTICATION STARTER

FILES
- index.html: homepage with Supabase email sign-up/sign-in/sign-out.
- interview.html: requires a signed-in Supabase session before showing the practice simulator.

IMPORTANT SETUP
1. Open both HTML files in a plain-text editor.
2. In BOTH files, find: PASTE_YOUR_SB_PUBLISHABLE_KEY_HERE
3. Replace it with the publishable key beginning sb_publishable_ from your Supabase project. Keep the surrounding single quotes.
4. The Project URL is already set to https://bauelyrvenoxitbjfpoo.supabase.co. Confirm it matches your Mumbai project.
5. Save both files. Upload/replace index.html and interview.html in the root of your GitHub repository, then commit changes.
6. Wait for GitHub Pages deployment and test sign-up with an email address you control. Confirm the email if Supabase asks. Then sign in.

SUPABASE AUTH SETTINGS
- Email provider enabled.
- Site URL: https://singhlovish87-hub.github.io/SSB-COMMAND/
- Redirect URL allowlist includes https://singhlovish87-hub.github.io/SSB-COMMAND/**

LIMITATIONS / SECURITY
- This is an authentication starter, not the finished commercial service.
- Do not collect real PIQ details or sensitive candidate data yet.
- Do not add secret/service_role keys to either HTML file or GitHub. Only the publishable key belongs in browser code.
- The interview page's session check is a user-interface gate, not sufficient protection for database records or paid access. Server-side authorization, secure trial enforcement, AI API proxying, payment verification, privacy notice, and admin controls are still required.
- The existing simulator still uses fixed/browser-generated questions; it is not yet a real LLM-powered interviewer.
