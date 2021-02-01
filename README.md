# docker-run-odoo

```
# Clone enterprise addons if needed
rm -rf enterprise
git clone <enterprise-repo> enterprise

# Run Odoo
sudo chmod -R 777 etc
docker-compose up -d

# Or just run docker-compose up to see log
docker-compose up

# To see odoo log
tail -fn 500 etc/odoo-server.log
```
