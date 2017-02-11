# Deploy Notes

* Will need to install `pip3 install pywebpush` manually for push notifications
* Will need to install `pip3 install aiohttp_cors` to fix some errors. Issue to be fixed in https://github.com/home-assistant/home-assistant/pull/5394
* If google verification needs to take place, edit `/srv/homeassistant/homeassistant_venv/lib/python3.4/site-packages/homeassistant/components/frontend/templates/index.html`
* MySQL Setup:
  * `sudo apt-get install libmysqlclient-dev mysql-server`
  * `pip3 install mysqlclient`
