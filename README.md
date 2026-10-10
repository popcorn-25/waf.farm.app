# waf.farm.app

Self-maintained application packages for the waf.farm app store (e.g. database binaries). Each application owns one rolling Release tag (db-mysql, db-mariadb, db-postgresql, db-redis) with versioned archives plus manifest.json; the panel installer reads the manifest, no panel release needed for patch bumps.
