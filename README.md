# Vinyl Vault

A private record-collection interface hosted on GitHub Pages, with authentication, database records and private cover images in Supabase.

The public repository contains interface code and a publishable Supabase key only. It contains no collection database, album data, private artwork, backups, service key or password. Database and storage access are enforced by Supabase row-level security, not by hiding the public key.

Open the Pages website and request an email sign-in link for the authorized owner account. Open the link on the same device. Changes made on phone and laptop use the same online collection. Use Refresh to retrieve edits made on another device.

Features include cover gallery, table browsing, search and filters, collector metadata, separate sleeve/record condition, duplicate warnings, precise purchase prices, optimistic edit conflict detection, recoverable Trash, CSV export and full JSON backup including cover bytes.

The original local app remains a separate copy. Its SQLite database does not automatically sync with the website. Keep full backups private. Supabase Free projects may pause after a week of low activity; the owner can resume the project from the Supabase dashboard.

Supabase client SDK version: 2.118.0, bundled locally. No runtime CDN is required. Interface build/source and schema/recovery utilities are also supplied to the owner in the local cloud-delivery folder.
