I created this EV Charging card for Home assistant Dashboard

It uses Picture element card and displays custon images based on charger status

Empty parking bay if charger is not connected to card
Parked car connected to charger if its plugged in
Animated energy flow gif if car is charging

It also disaplys the charger energy, elapse time and cost of charge

I used Modbus TCP for the Victron EV charger connection

Entities used

sensor.evse_chargerstatus                  -  Used for conditional card to display different pictures
switch.evse_startstopcharging              -  Used to start and stop charging
sensor.victron_ev_charger_power_ussage     -  Used to display charging power
sensor.victron_ev_charger_session_time     -  Used to dispaly current elapse charging time
sensor.km74pxw_state_of_charge             -  Used to display current state of charge
sensor.victron_ev_charging_cost            -  Used to dispaly current charging cost

Pictures Used
/local/Victron/NoCar.png                   -  No Car connected to charger
/local/Victron/ChargingAni.gif             -  Charging Animation
/local/Victron/NotCharging.png             -  Not charging animation





https://github.com/user-attachments/assets/f544bdc3-e6a2-4a70-bac9-e1002ebc74b0

