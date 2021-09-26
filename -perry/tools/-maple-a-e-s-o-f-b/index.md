---
title: MapleAESOFB
---
//[Perry](../../../index.html)/[tools](../index.html)/[MapleAESOFB](index.html)



# MapleAESOFB



[jvm]\
open class [MapleAESOFB](index.html)

#### Author



이재왕



## Constructors


| | |
|---|---|
| [MapleAESOFB](-maple-a-e-s-o-f-b.html) | [jvm]<br>open fun [MapleAESOFB](-maple-a-e-s-o-f-b.html)(iv: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;, mapleVersion: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [checkPacket](check-packet.html) | [jvm]<br>open fun [checkPacket](check-packet.html)(packet: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>open fun [checkPacket](check-packet.html)(packetHeader: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [decrypt](decrypt.html) | [jvm]<br>open fun [decrypt](decrypt.html)(ddata: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt; |
| [encrypt](encrypt.html) | [jvm]<br>open fun [encrypt](encrypt.html)(data: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt; |
| [getIVKeys](get-i-v-keys.html) | [jvm]<br>open fun [getIVKeys](get-i-v-keys.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt; |
| [getNewIv](get-new-iv.html) | [jvm]<br>open fun [getNewIv](get-new-iv.html)(oldIv: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt; |
| [getPacketHeader](get-packet-header.html) | [jvm]<br>open fun [getPacketHeader](get-packet-header.html)(length: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt; |
| [getPacketLength](get-packet-length.html) | [jvm]<br>open fun [getPacketLength](get-packet-length.html)(packetHeader: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [shuffleIV](shuffle-i-v.html) | [jvm]<br>open fun [shuffleIV](shuffle-i-v.html)(inputByte: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), in: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt;): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt; |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


## Properties


| Name | Summary |
|---|---|
| [iv](iv.html) | [jvm]<br>private open var [iv](iv.html): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)&gt; |

