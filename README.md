# UBLOX-GNSS-REPORT-GENERATOR
*nods*
1. make drive:
mkdir c:\GNSS_Evidence\

2. download and install for use with U-blox7 GPS/GLONASS usb : 
https://content.u-blox.com/sites/default/files/2025-06/u-center_v25.06_installer.zip

3.install: 
pip install pyserial
python -m pip install python-docx --user

4: change variables in GNSS_scanner.py
IE.COM7 and baude 38400

5.run ublox_data.py in cmd using python to generate data, let run past 420
python ublox_data.py

6. run GNSS_REPORT.py in cmd using python to generate written fileable report

7.enter name

8. enter DOB

9.FIle report

Author : Christopher T. WIlliams
