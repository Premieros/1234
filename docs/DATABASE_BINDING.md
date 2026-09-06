# Database Binding

This repository is permanently bound to the following Supabase project unless an explicit migration plan changes it:

- Repository: `Premieros/1234`
- Branch: `main`
- Supabase project ref: `scpovyrqmsbiduanykod`
- Supabase project name: `pos.v2`
- API URL: `https://scpovyrqmsbiduanykod.supabase.co`

## Mandatory guardrail

Do not point this repository, its CI, migrations, local environment, or deployed frontend to any other Supabase project by accident. Before database work, verify the project ref is exactly `scpovyrqmsbiduanykod`.

Only publishable/anon credentials may be used in browser-side environment variables. Never commit a service-role key, database password, access token, or other privileged secret.
