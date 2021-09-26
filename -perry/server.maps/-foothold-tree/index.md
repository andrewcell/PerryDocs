---
title: FootholdTree
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[FootholdTree](index.html)



# FootholdTree



[jvm]\
class [FootholdTree](index.html)(p1: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), p2: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), depth: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [findBelow](find-below.html) | [jvm]<br>fun [findBelow](find-below.html)(p: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Foothold](../-foothold/index.html)? |
| [findWall](find-wall.html) | [jvm]<br>fun [findWall](find-wall.html)(p1: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), p2: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Foothold](../-foothold/index.html)? |
| [insert](insert.html) | [jvm]<br>fun [insert](insert.html)(f: [Foothold](../-foothold/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [center](center.html) | [jvm]<br>val [center](center.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [depth](depth.html) | [jvm]<br>val [depth](depth.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [footholds](footholds.html) | [jvm]<br>val [footholds](footholds.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[Foothold](../-foothold/index.html)&gt; |
| [maxDropX](max-drop-x.html) | [jvm]<br>var [maxDropX](max-drop-x.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [minDropX](min-drop-x.html) | [jvm]<br>var [minDropX](min-drop-x.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [ne](ne.html) | [jvm]<br>var [ne](ne.html): [FootholdTree](index.html)? = null |
| [nw](nw.html) | [jvm]<br>var [nw](nw.html): [FootholdTree](index.html)? = null |
| [p1](p1.html) | [jvm]<br>val [p1](p1.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [p2](p2.html) | [jvm]<br>val [p2](p2.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [se](se.html) | [jvm]<br>var [se](se.html): [FootholdTree](index.html)? = null |
| [sw](sw.html) | [jvm]<br>var [sw](sw.html): [FootholdTree](index.html)? = null |

