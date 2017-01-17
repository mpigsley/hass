# Deploy Notes

* Will need to install `pip3 install pywebpush` manually for push notifications
* Will need to install `pip3 install aiohttp_cors` to fix some errors. (Might be fixed in later updates)
* If google verification needs to take place, edit `/srv/homeassistant/homeassistant_venv/lib/python3.4/site-packages/homeassistant/components/frontend/templates/index.html`
* MySQL Setup:
  * `sudo apt-get install libmysqlclient-dev mysql-server`
  * `pip3 install mysqlclient`
