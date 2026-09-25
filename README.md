# Album privé photos & vidéos

Supabase Auth protège l'accès et Storage conserve les médias dans un bucket privé. Ne mets jamais la service_role key dans le navigateur.

1. Crée un projet Supabase gratuit.
2. Crée un bucket privé nommé family-media.
3. Exécute schema.sql dans SQL Editor.
4. Crée les comptes famille dans Authentication > Users.
5. Mets l'URL Supabase et la clé publishable/anon dans config.js.
6. Active GitHub Pages sur main/root.
