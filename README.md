# LAITHÉ PARFUMS
Cloudflare Workers + Static Assets + D1.
1. أنشئ D1 باسم `laithe-parfums-db`.
2. ضع database_id الحقيقي في wrangler.toml.
3. نفذ schema.sql على D1.
4. أضف Secret باسم ADMIN_SECRET في Cloudflare، ولا تضع كلمة المرور في GitHub.
5. اربط GitHub ثم Deploy.
