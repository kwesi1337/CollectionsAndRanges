** The examples in this text is taken from the GoogleMap App.**

The published version of this app made by [Timm Rasmussen, Waqas Mohiuddin, Joakim Toftgaard-Hansen, Joseph Awwal](https://github.com/x) can be found on Google Play

[Rational Calculator](https://play.google.com/store/apps/details?id=dk.cphbusiness.template)

## What is Collections?
A collection framework i
In Kotlin, there is a distinction between mutable and immutable collections(lists, sets, maps). There is control over exactly  when collections can be edited, which is useful for finding and eliminating bugs, and for API design.

The Kotlin List<out T> type is an interface that provides read only operations.


## How to implement Collections?
![picture alt](http://imgur.com/TRA63sd.png)

  
## Other uses for Collections
Sometimes you want to return a snapshot of a collection to the caller at a specific time, and that shouldnt change.
![picture alt](http://imgur.com/6TKo5mA.png)

The toList method above duplicates the list items, thus the returned list is guaranteed to never change.

-------------------------------------------------------------------------------------------------------------------------------

## What is Ranges?
Range expressions are formed with the rangeTo function that uses the operator form " .. "
Range is defined for any comparable type.


## How to implement Ranges?
![picture alt](http://imgur.com/eCkDHMF.png)

Integral type ranges like (IntRange, LongRange, CharRange) have extra features: they can be iterated over.
![picture alt](http://imgur.com/9IHJV9z.png)
## Other uses for Ranges?
