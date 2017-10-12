Ai-Thinker GPRS AT module change list
=====

> A : Alpha
> B : Beta
> RC: Release Candidate
> R : Release 


------------------------------------------------
## V1.6R:

#### Add feature:

* AT+LOCATION=2
get location(latitude and longitude) through gps


#### Remove feature:

None

#### Update feature:

None

#### Bug fix:


-------------------------------------------

------------------------------------------------
## V1.5RC:

#### Add feature:

None

#### Remove feature:

None

#### Update feature:

None

#### Bug fix:

* fix bug no voice and can not speak at all when use call!

-------------------------------------------


------------------------------------------------
## V1.4:

#### Add feature:

* AT+CCLK:
command `AT+CCLK="AUTO"` can enable auto adjust rtc time on gprs attached, and it will be remembered, cacel auto update time by command`AT+CCLK="YY/MM/DD,hh:mm:ss+zz"`.

* AT+LOCATION=1
get location(latitude and longitude) through gprs(LBS)

~~* AT+SPEEDTEST~~
~~just for test!!!~~

#### Remove feature:
None

#### Update feature:

* AT+CCLK:
fixed ack length as as 20. now: "YY/MM/DD,hh:mm:ss+zz"

* Power on info optimize
remove SIM card info on start up, if find no sim card, print NO Simcard

#### Bug fix:

-------------------------------------------

## v1.0:

#### Add feature:

* AT+AGPS
command `AT+AGP=1` to enable agps

* AT+GIZ****
`AT+GIZSTART` to connect gizwits
`AT+GIZSEND`  to send data to gizwits
`AT+GIZSTOP`  to disconnect from gizwits
`AT+GIZTRACKER` to upload location info to gizwits app
`AT+GIZQRCODE`  save gizwits device QR code string

* AT+GPAUPGRADE
step into upgrade gps firmware mode


