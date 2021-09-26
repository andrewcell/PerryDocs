---
title: giveBuff
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[giveBuff](give-buff.html)



# giveBuff



[jvm]\
open fun [giveBuff](give-buff.html)(buffid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), bufflength: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), statups: [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[BuffStat](../../client/-buff-stat/index.html), [Integer](https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html)>>): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>



It is important that statups is in the correct order (see decleration order in BuffStat) since this method doesn't do automagical reordering.



#### Return



## Parameters


jvm

| | |
|---|---|
| buffid |  |
| bufflength |  |
| statups |  |




