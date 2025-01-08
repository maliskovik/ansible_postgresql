# Postgresql
Postgresql ansible role.
Installs and configuires postgresql.

# Optional variables
* postgresql_install - server or client (only) install.
* postgresql_port - port postgresql will listen on
* postgresql_ssl_cert - location of the postgresql cert file(on remote)
* postgresql_ssl_key - location of the postgresql key file(on remote)
* postgresql_locale - locale to use on postgresql
* postgresql_version - Version of postgresql to install
* postgresql_repo - repository to use for this install
* postgresql_repo_key - repository key to use
