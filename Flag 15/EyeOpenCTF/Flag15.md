# Flag 15
They give us the following hint: **the treasure stored in flag.php**
We are presented with this page:

![1c0397e2c8c019b6e451ee5e0e5184de.png](../_resources/1c0397e2c8c019b6e451ee5e0e5184de.png)

I tried to play with the **category** parameter during long time and the following payload got a hit: **php://filter/convert.base64-encode/resource=index**

![8fed3e948a5eaa7c609c8cd11f56746d.png](../_resources/8fed3e948a5eaa7c609c8cd11f56746d.png)

I tried to replace "index" with "flag" but it did'nt return anything useful, so I tried a simple path traversal and it worked.

![cb3a38204aeb96533c1423fe94ca2d35.png](../_resources/cb3a38204aeb96533c1423fe94ca2d35.png)

![ccef64cc3ef759d3f67e4f0859b80a49.png](../_resources/ccef64cc3ef759d3f67e4f0859b80a49.png)