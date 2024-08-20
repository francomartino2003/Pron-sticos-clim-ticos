DATA DICTIONARY
time: Time at which the forecast model is initialized (i.e. when the forecast was made). Hour is in UTC zone.
step: How many six hour steps ahead the model is forecasting (expressed in day-hour). From 0 days 0 hours to 15 days.
latitude: Self explanatory. 0.5 degree resolution.
longitude: Self explanatory. 0.5 degree resolution.
valid_time: Time being forecasted. Hour is in UTC zone.
t2m: Temperature at 2 meters. Expressed in Kelvin degrees. Data represents an average value over the grid and over the 6 hour period.

COMMENTS
There’s missing data for July and August 2017. This is due to damaged data tapes in the ECMWF archive. It may or may not be available in the future. You can read more about it here: https://confluence.ecmwf.int/display/UDOC/MARS+data+unavailability+in+ECMWF+tape+library?type=dataset&val=tigge

For a more detailed documentation read: https://confluence.ecmwf.int/display/TIGGE