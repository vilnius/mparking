# Data from m.Parking system

m.Parking is an app that could be used for parking your car within Vilnius city parking places. As a system, it also incorporates the processing of SMS'es that are being sent to the number 1332.
There are a few datasets that we found as interesting at the moment, we will probably extend and automate it later.

- history.csv is a file containing the historical records for where what phone parked what car. Unfortunately it does not have a timestamp, which makes it a pretty awful and useless dataset.
- operators.csv this is a metadata file describing the operators whose ID's are used in other datasets.
- parking_places.csv these are the parking places that are used for zone capacity counting and they are marked all over the city.
- received_sms.csv - here you will find the received SMS'es for a few days. The table is being cleaned up for performance purposes, also we trim the body of the SMS for depersonalisation.
- zones.csv this is a metadata file identifying what zones exist in the city.
- parking_inspection.csv is a big dataset showing the inspections of parked cars. Workers of municipality entity are in charge of checking whether the car is parked right and that's where the data is collected.
- violations.csv - if the car is not parked right, a violation report is issued.

In the mtis_schema.csv file you will find the existing table names and amounts of they data they contain in.

If you have any questions shoot us an email on open@vilnius.lt
