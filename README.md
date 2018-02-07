# ScalaFun


scala> def sum (func : Int =>Int,lb:Int,ub:Int)={
     | var total = 0
     | for(element <-lb to ub){
     |  total +=func(element)
     | }
     | total
     | }
sum: (func: Int => Int, lb: Int, ub: Int)Int

scala> def id(i:Int)=i
id: (i: Int)Int
