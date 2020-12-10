# ISG-Attack

We use the codes of XMSS and K2SN-MSS from
https://github.com/XMSS/xmss-reference/commit/fb7e3f8edce8d412a707f522d597ab3546863202
https://github.com/skarati/K2SN-MSS
respectively to perform the attack.

The isg attack on XMSS is available in the /xmss-mt-isg/isg-attack-xmss.c and /xmss-mt-isg/isg-attack-xmss.h files. Makefile compiles
the /xmss-mt-isg/test/main.c file to create an executable one.

For isg-attack on K2SN-MSS, the code is available at /k2snmss-isg/main.c and /k2snmss-isg/main.h files. Makefile compiles the 
/k2snmss-isg/main.c file to create an executable one.



