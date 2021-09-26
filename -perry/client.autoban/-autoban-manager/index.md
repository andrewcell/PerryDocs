---
title: AutobanManager
---
//[Perry](../../../index.html)/[client.autoban](../index.html)/[AutobanManager](index.html)



# AutobanManager



[jvm]\
class [AutobanManager](index.html)(**chr**: [Character](../../client/-character/index.html))



## Functions


| Name | Summary |
|---|---|
| [addMiss](add-miss.html) | [jvm]<br>fun [addMiss](add-miss.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [addPoint](add-point.html) | [jvm]<br>fun [addPoint](add-point.html)(fac: [AutobanFactory](../-autoban-factory/index.html), reason: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [getLastSpam](get-last-spam.html) | [jvm]<br>fun [getLastSpam](get-last-spam.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [resetMisses](reset-misses.html) | [jvm]<br>fun [resetMisses](reset-misses.html)() |
| [setTimestamp](set-timestamp.html) | [jvm]<br>fun [setTimestamp](set-timestamp.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), time: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Timestamp checkertype:<br></br> 0: HealOverTime<br></br> 1: Pet Food<br></br> 2: ItemSort<br></br> 3: ItemIdSort<br></br> 4: SpecialMove<br></br> 5: UseCatchItem<br></br> |
| [spam](spam.html) | [jvm]<br>fun [spam](spam.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [chr](chr.html) | [jvm]<br>val [chr](chr.html): [Character](../../client/-character/index.html) |
| [lastMisses](last-misses.html) | [jvm]<br>var [lastMisses](last-misses.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [lastTime](last-time.html) | [jvm]<br>val [lastTime](last-time.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[AutobanFactory](../-autoban-factory/index.html), [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)> |
| [misses](misses.html) | [jvm]<br>var [misses](misses.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [points](points.html) | [jvm]<br>val [points](points.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[AutobanFactory](../-autoban-factory/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [sameMissCount](same-miss-count.html) | [jvm]<br>var [sameMissCount](same-miss-count.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [spam](spam.html) | [jvm]<br>var [spam](spam.html): [LongArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long-array/index.html) |
| [timestamp](timestamp.html) | [jvm]<br>var [timestamp](timestamp.html): [IntArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int-array/index.html) |
| [timestampCounter](timestamp-counter.html) | [jvm]<br>var [timestampCounter](timestamp-counter.html): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |

