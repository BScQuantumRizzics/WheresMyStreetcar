# WheresMyStreetcar
Predicting Delays on TTC Streetcar Routes

### Daytime Routes
> 501 Queen 
> 503 Kingston Road  
> 504 King  
> 505 Dundas  
> 506 Carlton  
> 507 Long Branch  
> 508 Lake Shore  
> 509 Harbourfront  
> 510 Spadina  
> 511 Bathurst  
> 512 St. Clair  

#### Blue Night Routes
> 301 Queen  
> 303 Kingston Road  
> 304 King  
> 305 Dundas  
> 306 Carlton  
> 310 Spadina  
> 312 St. Clair  


## TTC Streetcar Delay Data Description

|Field Name|Description|Example|
|----------|-----------|--------|
|Report Date|The date (YYYY/MM/DD) when the delay-causing incident occurred|2024/12/12|
|Route|The number of the streetcar route|505|
|Time|The time (hh\:mm\:ss AM/PM) when the delay-causing incident occurred|12\:34\:56 AM|
|Day|The name of the day|Tuesday|
|Location|The location of the delay-causing incident|Queen and Spadina|
|Incident|The description of the delay-causing incident|Mechanical|
|Min Delay|The delay, in minutes, to the schedule for the following streetcar|15|
|Min Gap|The total scheduled time, in minutes, from the streetcar ahead of the following streetcar|25|
|Vehicle|Fleet Number|4504|

*Direction has been omitted as it is irrelevant
