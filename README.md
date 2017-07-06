# PhoneNumberVerification
Example code for using the Phone Number Verification Sefvice

By downloading the attached file and adding the Access token for your SDC application 
you can quickly try out the Syniverse Phone number Verification API.

You will first need to have an account (create at https://developer.syniverse.com )
And to have created your sample application using Applications -> New Application
You will then need to enable the Phone Number Verification and Gateway Services
Using the Settings option for your new application.

Sample output from the file is

python.exe phone-number-check-example-external.py

status code: 200
response: {"numberidentity":{"number":"+447860438585","validity":"true","carrier_id":"18149","carrier_name":"VODAFONE (C&W)","number_type":"M","country_iso_code":"GBR","country":"United Kingdom","carrier_mcc":"234","carrier_mnc":"15","account_type":"","last_known_event":"None","previous_carrier_id":"","previous_carrier_name":""},"tracking_id":"200290035881499172651890"}

status code: 200
response: {"numberidentity":{"number":"+447513005998","validity":"true","carrier_id":"8584","carrier_name":"TELEFONICA UK","number_type":"M","country_iso_code":"GBR","country":"United Kingdom","carrier_mcc":"234","carrier_mnc":"10","account_type":"","last_known_event":"None","previous_carrier_id":"","previous_carrier_name":""},"tracking_id":"200290035881499172652541"}

status code: 200
response: {"numberidentity":{"number":"+442079202200","validity":"true","carrier_id":"11500","carrier_name":"BT","number_type":"L","country_iso_code":"GBR","country":"United Kingdom","account_type":"","last_known_event":"None","previous_carrier_id":"","previous_carrier_name":""},"tracking_id":"200290035881499172653146"}

status code: 200
response: {"numberidentity":{"number":"+446543211234","validity":"false","carrier_id":"","carrier_name":"","number_type":"","country_iso_code":"","country":"","carrier_mcc":"","carrier_mnc":"","account_type":"","last_known_event":"","porting_date":"","previous_carrier_id":"","previous_carrier_name":"","deactivation_date":""},"tracking_id":"200290035881499172653737"}

status code: 200
response: {"numberidentity":{"number":"+18136375000","validity":"true","carrier_id":"21568","carrier_name":"ZIPWHIP\/FRONTIER COMMUNICATIONS SMSENABLED - FRONTIER COMMUNICATIONS - SYNIVERSE","number_type":"L","country_iso_code":"USA","country":"United States","account_type":"","last_known_event":"Ported","porting_date":"2008-05-09T00:00Z","previous_carrier_id":"","previous_carrier_name":""},"tracking_id":"200290035881499172654492"}

status code: 200
response: {"numberidentity":{"number":"+18133824424","validity":"true","number_type":"M","country_iso_code":"USA","country":"United States","carrier_mcc":"310","carrier_mnc":"150","account_type":"","last_known_event":"Deactivated","previous_carrier_id":"1025","previous_carrier_name":"AT&T WIRELESS","deactivation_date":"2012-10-06T00:00Z"},"tracking_id":"200290035881499172655096"}

Process finished with exit code 0

