FROM odoo:8.0

ENTRYPOINT ["/entrypoint.sh"]

CMD ["openerp-server", "--database", "$DOCKER_DB_NAME", "--db-filter", "^$DOCKER_DB_NAME$"]
