# Deploy Notes

* Will need to install `pip3 install pywebpush` manually for push notifications
* Will need to manually [setup ecobee](https://home-assistant.io/components/ecobee/) by adding the api key to `configuration.yaml`
* If google verification needs to take place, edit `/srv/homeassistant/homeassistant_venv/lib/python3.4/site-packages/homeassistant/components/frontend/templates/index.html`
* MySQL Setup:
  * `sudo apt-get install libmysqlclient-dev mysql-server`
  * `pip3 install mysqlclient`
* Add Z-Wave Node
  1. `cd /srv/homeassistant/src/open-zwave-control-panel`
  2. `sudo ./ozwcp -p 8888`
  3. Edit Configuration -> Save Configuration
  4. `sudo cp zwscene.xml /home/homeassistant/.homeassistant/`
  5. `sudo cp zwcfg_0xd4b7980d.xml /home/homeassistant/.homeassistant/`

# TODO

* Add automation for Apple TV
* Add/Remove Sensors from home mode based on occupation
* Alexa, run/reset thermostat
