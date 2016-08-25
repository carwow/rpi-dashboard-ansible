Provisioning script used to set up Raspberry Pi dashboards, see this guide:

https://medium.com/carwow-product-engineering/how-to-build-cheap-and-easy-data-dashboards-for-your-startup-400b304af110


### TODO:

* Fix reboot error (ansible only?)
* Split tasks/roles better
* See if it's possibler to setup the hostname via ansible (with user input) automatically when the RPI is provisioned the first time
* Setup cron jobs to switch screens off/on based on working days/hours
* Add script/role/task to Setup a new homepage for the kiosk
