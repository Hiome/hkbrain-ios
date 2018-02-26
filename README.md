# Bernard

> *Barely Educated Rather Neurotic Automation Relay Device*

Bernard is a semi-intelligent home automation assistant that controls your home via HomeKit. It uses a variety of heuristics to better guess what you might want, so your home can work for you without you having to explicitly control everything.

It basically provides smart HomeKit triggers. For example, when you come home, Bernard can use occupancy detectors to welcome you home and turn the lights on, but not if people are already asleep.

Currently, Bernard has several limitations:

* Rules must be programmed into Bernard. These obviously differ from home to home. My goal is to be able to analyze usage patterns and automatically train Bernard, but this will require many more sensors first.
* Bernard must be constantly running in the foreground of an iOS device. This is a limitation of HomeKit and will hopefully go away in a future iOS release.

TODO:

* Create a companion app that integrates HealthKit to provide more personalized messages and coaching
* Create a companion app that talks to iBeacons

