Xcode Hardware Performance
==========================

These are the results from running Xcode on a non-trivial open source project using various Macs. The goal is to give developers a relative idea of how each computer model compares to one another. Read the [specifics](#specifications) and [contributing](#contributing) sections for more info.

Computer Model | CPU | RAM | Fresh Build Time | Incremental Build Time |
-------------- | --- | --- | ---------------- | ---------------------- |
MacBook (Retina, 12-inch, Early 2015) | 1.1 GHz Intel Core M | 8 GB | 3:00 | 0:12
MacBook Pro (Retina, 15-inch, Early 2013) | 2.4 GHz Intel Core i7 | 8 GB | 0:47 | 0:10
MacBook Pro (Retina, 15-inch, Mid 2014) | 2.2 GHz Intel Core i7 | 16 GB | 0:51 | 0:07
iMac (HDD 1 TB, 21.5-inch, Late 2012) | 2.7 GHz Intel Core i5 | 8 GB | 4:15 | 0:33
iMac 5K (512GB Flash, 27-inch, Late 2015) | 4.0Ghz Intel Core i7 | 32 GB | 0:28 | 0:06|
Mac Pro (Flash Storage, Late 2013) | 3.5 GHz 6-Core Intel Xeon E5 | 32 GB | 0:30 | 0:05
MacBook Pro (15-inch, Early 2011, SSD) | 2.0 GHz Intel Core i& | 8 GB | 1:01 | 0:10 



Specifications
--------------

For the test, I decided to use an app that I actually work on: [eidolon](https://github.com/artsy/eidolon). 

For "fresh" builds, I cleaned the build folder (⌘⇧K) repeatedly until it worked with no permissions problems. Then I sat and waited for Xcode to index the project. I also made sure the simulator was _closed_, so these times include booting the simulator and launching the app. Then I hit ⌘R and start a timer, only ending it when the app had fully launched.

"Incremental" builds represent a more common use case: changing one file and recompiling with the simulator already running. I added `print("hello!")` to `application(: didFinishLaunchingWithOptions:)` and hit ⌘R, timing the time it took for the app to launch. 

I repeated each test a few times and took their average times. 

Contributing
------------

It would be super-cool if we could perform the above tests on a variety of machines and consolidate the results here. You can [follow the instructions](https://github.com/artsy/eidolon#downloading-the-code) to download the code and the project dependencies, and send a pull request adding your own results. I'd super-appreciate it! :bow:

Please note that this project is released with a Contributor Code of Conduct. By participating in this project, you agree to abide by [its terms](/Code of Conduct.md).

License
-------

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
