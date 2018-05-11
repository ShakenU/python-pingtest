# python-pingtest
A python script for doing ping testing. Useful if your internet keeps dropping but your ISP refuses to do anything about it. 

Written by Gavin Underdown, available under the GNU GPL v3 (or later)

Usage: 

Download script 
Add in your gateway to the source code (optional)
Execute script `./pingtest.py`

Program logs failures (with date and time information) to `~/ping_log.txt`

Windows Support: You're on your own

Sample Output: 
```
Ping to 35.153.128.254 (AWS US-East 1) failed at 2018-05-11 16:52:12.419382 (1526075532)
Ping to www.microsoft.com (Microsoft) failed at 2018-05-11 16:52:12.424583 (1526075532)
Ping to 13.52.0.0 (AWS US-West 1) failed at 2018-05-11 16:52:12.426706 (1526075532)
Ping to www.google.com (Google) failed at 2018-05-11 16:52:12.431716 (1526075532)
Ping to www.debian.org (Debian) failed at 2018-05-11 16:52:12.434494 (1526075532)
Ping to 35.153.128.254 (AWS US-East 1) failed at 2018-05-11 16:52:13.438439 (1526075533)
Ping to www.microsoft.com (Microsoft) failed at 2018-05-11 16:52:13.440925 (1526075533)
Ping to 13.52.0.0 (AWS US-West 1) failed at 2018-05-11 16:52:13.443604 (1526075533)
Ping to www.google.com (Google) failed at 2018-05-11 16:52:13.448416 (1526075533)
Ping to www.debian.org (Debian) failed at 2018-05-11 16:52:13.450825 (1526075533)
```

