FROM odoo:8.0

ENTRYPOINT ["/entrypoint.sh"]

CMD ["openerp-server", "--database", "$DOCKER_DB_NAME", "--dbfilter", "^$DOCKER_DB_NAME$"]
