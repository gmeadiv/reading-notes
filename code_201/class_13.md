# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS
- [From Here](http://diveinto.html5doctor.com/storage.html)

## Problem: web applications don't have the same ability as native client apps to locally store large amounts of data
- cookies unecessarily send the same maount of data over and over
- cookies send data unencrypted
- cookes are limited to only 4kb of data
- too small to be useful but big enough to slow down the web application
- what is needed: lots of spcae, on the client, that perists beyond page refresh, isn't transmitted to the server

## Local storage hacks before HTML5
- specific to single browser or
- reliant on third party plug in

## Introducing HTML5 storage
- web pages can store key/value pairs locally
- check if my browser supports it

## Using HTML5 Storage
- store data based on a named key, then retrieve it with the same key
- the key is a string
- the data can be anything sujpported by JavaScript but the data is stored as a string