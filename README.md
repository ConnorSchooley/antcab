# antcab
Antcab is the name I have given to a cipher I have created. Basically, antcab is an advanced version of a shift cipher. This script is able to encode and decode with both the default key and custom keys.

## information
The way antcab works is, there is 6 letter key (default = "antcab"). The key is split into 2, 3-letter words ("ANT", "CAB") and then the difference of the letters in corresponding positions are recorded. ('A' -> 'C' is a diffence of 2). The shift value of the three sets of shifts (2, -13,-18) repeats to either encode or decode the message. 

Example : (mickey)VLMU MW C ZITC RKGI ESHG -> This is a very nice code

# A sample run
```bash
Default Key (y/n): y
Mode (e/d) - e
Enter your message for encoding:This is a message
VUQU VA C ZMUFIIR
```
