# CliPhoT | 🖱️💥⏱️
**CLI**ck to **PHO**ton latency **T**imer

![cliphotest](https://user-images.githubusercontent.com/55419973/212254368-8acf8208-8d4b-4126-9289-03ec34fec686.gif)

## Prototype 2 Update:
The long overdue perfboard prototype is here featuring an upgraded Arduino Pro Micro with a Type-C port, which makes CliPhoT more durable and much easier to operate. A wiring diagram will be provided soon:tm:.
This upgrade is another step towards having custom a PCB print for an extremely easy assembly process.

<img src="https://github.com/archead/CliPhoTv2/assets/55419973/9e8627d6-f1b4-4668-8d3b-c617e46ca060" width="480">

# Below is the v1 readme, everything still applies to v2.

## What it does:
This device attempts to simplify the testing of input latecy in video games by measuring the time it takes for something to happen on a monitor after a mouse click (or any other type of input) has occured.
Using this method, it takes into consideration everything that can introduce input latency.

## The Interface:
<img src="https://user-images.githubusercontent.com/55419973/212255234-c514adb5-481b-4d23-8197-ddebac0c5032.JPG" width="320">

CliPhoT's interface provides a quick overview of your current test run by display the current average, minimum and maximum times.

Holding down the input key for 2 seconds after a time has been recorded will reset all current statistics.

## CliPhoT's Latency
On it's own, CliPhoT should only add 4-8 additional microseconds of latency which should not skew the results by a significant amount.

## TODO's
- Schematics, parts list and software guide
- Companion software to display more information via a connected PC
