# MacOSXservices
tests using Automator &amp; services on Mac OS X


also R: spoof MAC adress:  
```sudo ifconfig en0 ether $(perl -e 'for ($i=0;$i<5;$i++){@m[$i]=int(rand(256));} printf "02:%X:%X:%X:%X:%X\n",@m;') && sudo ifconfig en0 down && sudo ifconfig en0 up```
