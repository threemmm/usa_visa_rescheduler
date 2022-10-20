# visa_rescheduler
US VISA (ais.usvisa-info.com) appointment re-scheduler - USA visa appointment in Canada - python


English Version


## Prerequisites
- **Having a US VISA appointment _already_ scheduled **
- Google Chrome installed (to be controlled by the script)
- Python v3 installed (for running the script)
- API token from Pushover and/or a Sendgrid (for notifications)


## Initial Setup
- Create a `config.ini` file with all the details required
- Install the required python packages: `pip3 install -r requirements.txt`
- Default setup `visa.py`: It checks Toronto, you can change `FACILITY_ID` to the city you want 
- (you can find the facility id on the website HTML elements)
- Default setup `multi_cities_visa.py`: checks _Toronto, Montreal_ and _Vancouver_

## Executing the script
- Simply run `python visa.py`
- That's it! 

### Multi Cities
If you want to check multi cities and get the earliest date possible, you need to add their facility ids to `config.ini`
(`FACILITY_ID_LIST`) and run `python multi_cities_visa.py` instead of `visa.py` 

## Acknowledgement
Thanks to @yaojialyu for creating the initial script and to @cejaramillof for adapting it to Colombia!
