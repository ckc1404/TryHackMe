### N o T e S

---

* Topics covered :
  * Linux Security
  * Web Application Security
  * Network Security
  * Reverse Engineering
  * Forensics  

---

Day 1 : Inventory management !

* Simple challenge - We need to find the cookie and the fixed part which is v4er9ll1!ss.
* Then we need what mcinventory requested and we can get that by changing authentication id cookie to the value of mcinventory.
* We can get that using `echo -n 'mcinventoryv4er9ll1!ss' | base64`.

---

Day 2 : Arctic forum !

* Use disearch, find the password in the extension `/sysadmin` and use it to login as admin. 
* The third answer pops up after logging in !

---

Day 3 : Evil Elf

* Find the packet 998 using ctrl G, then follow it's TCP stream to find the christmas.txt file. 
* Using john the ripper we get password `rainbow`.

---

Continued...

---

Blah blah..

