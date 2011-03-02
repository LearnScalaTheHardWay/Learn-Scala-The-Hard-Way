Exercise 1: Get familiar with Scala command line
************************************************

Welcome to Scala version 2.7.7final (OpenJDK 64-Bit Server VM, Java 1.6.0_20).
Type in expressions to have them evaluated.
Type :help for more information.

scala> 1+3  
res0: Int = 4

scala> 1/3
res1: Int = 0

scala> 1//3
res2: Int = 1

scala> 1/3 
res3: Int = 0

scala> 1///3
res4: Int = 1

scala> 1////3
res5: Int = 1

scala> 1///////3
res6: Int = 1

scala> 1 / / 3  
<console>:1: error: ';' expected but integer literal found.
       1 / / 3
             ^

scala> 1 / /3 
<console>:1: error: ';' expected but integer literal found.
       1 / /3
            ^

scala> 1 // 3
res7: Int = 1

scala> 1 /// 3
res8: Int = 1

scala> 1 ///// 3
res9: Int = 1

scala> 1 / 3    
res10: Int = 0

scala> 1 / 3.0
res11: Double = 0.3333333333333333

scala> 1.0 / 3
res12: Double = 0.3333333333333333

scala> 1 / 3  
res13: Int = 0

scala> print("Aasd")
Aasd
scala> print("Aa\nsd")
Aa
sd
scala> print("Aa\\nsd")
Aa\nsd
scala> print("Aa\\n\tsd")
Aa\n	sd
scala> print("Aa\\ns\td")
Aa\ns	d
scala> print("Aa\ns\td") 
Aa
s	d
scala> println("Aa\ns\td")
Aa
s	d

scala> println("Aa\ns\td" + "eweq")
Aa
s	deweq

scala> println("Aa\ns\td" + "eweq" + 3)
Aa
s	deweq3

scala> println("Aa\ns\td" + "eweq" + 3 + 5)
Aa
s	deweq35

scala> println("Aa\ns\td" + "eweq" + 3 + (5 + 4))
Aa
s	deweq39

scala> 
