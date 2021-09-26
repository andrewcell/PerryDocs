---
title: ReactorStats
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[ReactorStats](index.html)



# ReactorStats



[jvm]\
class [ReactorStats](index.html)



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [addState](add-state.html) | [jvm]<br>fun [addState](add-state.html)(state: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), data: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[ReactorStats.Companion.StateData](-companion/-state-data/index.html)&gt;) |
| [getActiveSkills](get-active-skills.html) | [jvm]<br>fun [getActiveSkills](get-active-skills.html)(state: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;? |
| [getNextState](get-next-state.html) | [jvm]<br>fun [getNextState](get-next-state.html)(state: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [getReactItem](get-react-item.html) | [jvm]<br>fun [getReactItem](get-react-item.html)(state: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;? |
| [getStateSize](get-state-size.html) | [jvm]<br>fun [getStateSize](get-state-size.html)(state: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [getType](get-type.html) | [jvm]<br>fun [getType](get-type.html)(state: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Properties


| Name | Summary |
|---|---|
| [br](br.html) | [jvm]<br>var [br](br.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)? = null |
| [stateInfo](state-info.html) | [jvm]<br>val [stateInfo](state-info.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[ReactorStats.Companion.StateData](-companion/-state-data/index.html)&gt;&gt; |
| [tl](tl.html) | [jvm]<br>var [tl](tl.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)? = null |

