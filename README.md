[README.md](https://github.com/user-attachments/files/27789797/README.md)
# UAE CRM – GitHub Pages + Supabase Secure

Tento balík obsahuje frontend CRM aplikace napojený na Supabase.

## Konfigurace
- Supabase URL: https://ibocarzxamcqycuctixc.supabase.co
- Frontend key: publishable key vložený v `index.html`

## Nasazení na GitHub Pages
1. ZIP rozbalte.
2. Nahrajte obsah do GitHub repository.
3. Commitněte změny.
4. Settings → Pages → Deploy from branch → main / root.

## Funkce
- Přihlášení a registrace přes Supabase Auth.
- Noví uživatelé jsou `pending`.
- Owner/admin může schvalovat uživatele.
- Owner/admin vidí User Management a exporty.
- Sales user může editovat jen vlastní záznamy.
- Data se ukládají do Supabase.

## Poznámka
Schéma Supabase v2 musí být nainstalované a owner účet musí mít `role=owner`, `status=approved`.
