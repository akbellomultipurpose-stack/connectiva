CONNECTIVA — single-file frontend
================================

Files:
- index.html — complete HTML/CSS/JavaScript application.

Supabase:
- Project URL and publishable key are already configured in index.html.
- Never replace the publishable key with a service_role key.
- Email OTP must be enabled/configured in Supabase Auth.

Deploy:
1. Create/open your GitHub repository.
2. Upload index.html to the repository root.
3. Enable GitHub Pages from Settings > Pages.
4. Choose Deploy from branch and the main branch/root folder.
5. Open the generated Pages URL.

This build uses real Supabase Auth and database calls. Some advanced infrastructure
features (large-scale video processing, live streaming, WebRTC media relay, payments,
and external AI inference) require their corresponding service integrations.
