# UAE CRM Secure – English export fix v2

Deals export now starts with readable columns:
- companyName
- contactName
- salesRepName
- dealTitle

Technical UUID fields are moved to the end.

If export still starts with `id, company_id, contact_id, sales_rep_id`, the browser or GitHub Pages is still serving the old `index.html`. After upload, wait for deployment and press Ctrl + F5.
