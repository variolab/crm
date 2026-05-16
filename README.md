# UAE CRM Secure – English export fix

Fix:
- CSV exports now show readable names first:
  - companyName
  - contactName
  - salesRepName
- technical UUID values are moved to the end as `technical...` columns.
- CSV separator remains semicolon `;`.
- Supabase connection and existing permissions are preserved.

Deployment:
1. Unzip.
2. Upload `index.html`, `.nojekyll`, `README.md`.
3. Commit changes.
4. Press Ctrl + F5 after deployment.
