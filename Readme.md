Xcode Hardware Performance
==========================

These are the results from running Xcode on a non-trivial open source project using various Macs. The goal is to give developers a relative idea of how each computer model compares to one another. Read the [specifics](#specifications) and [contributing](#contributing) sections for more info.

🖥 |Computer Model | CPU | RAM | Fresh Build Time | Incremental Build Time |
--- | -------------- | --- | --- | ---------------- | ---------------------- |
💻 | MacBook </br>Retina, 12", Early 2015 | 1.1 GHz M | 8 GB | 3:00 | 0:12
💻 | MacBook </br>Retina, 12", Early 2015 | 1.2 GHz M | 8 GB | 2:28 | 0:12
💻 | MacBook </br>Retina, 12", Early 2016 | 1.2 GHz m5 | 8 GB | 2:10 | 0:12
💻 | MacBook Air </br>13", Mid 2012, 512 SSD | 2 Ghz i7 | 8 GB | 2:10 | 0:11
💻 | MacBook Air </br>13", Mid 2013, 128 SSD | 1.3 Ghz i5 | 4 GB | 2:58 | 0:24
💻 | MacBook Pro </br>13”, Mid 2010 512 SSD | 2.4 GHz Intel Core 2 Duo | 8 GB | 3:01 | 0:24
💻 | MacBook Pro </br>13", Early 2011, 512 SSD | 2.7 Ghz i7 | 8 GB | 2:30 | 0:16
💻 | MacBook Pro </br>13”, Mid 2012 256 SSD | 2.5 GHz i5 | 8 GB | 2:08 | 0:19
💻 | MacBook Pro </br>13", Early 2015, 1TB SSD | 3.1 Ghz i7 | 16 GB | 1:25 | 0:09
💻 | MacBook Pro </br>15", Early 2011 | 2.0 GHz i7 | 8 GB | 1:00 | 0:13
💻 | MacBook Pro </br>15" Early 2011, SSD | 2.0 GHz i7 | 8 GB | 1:01 | 0:10
💻 | MacBook Pro </br>Retina, 13", Early 2015 | 2.7 GHz i5 | 8 GB | 1:35 | 0:11
💻 | MacBook Pro </br>Retina, 15", Mid 2012 | 2.3 GHz i7 | 16 GB | 0:46 | 0:08
💻 | MacBook Pro </br>Retina, 15", Early 2013 | 2.4 GHz i7 | 8 GB | 0:47 | 0:10
💻 | MacBook Pro </br>Retina, 15", Late 2013 | 2.3 GHz i7 | 16 GB | 0:53 | 0:09
💻 | MacBook Pro </br>Retina, 15", Mid 2014 | 2.2 GHz i7 | 16 GB | 0:51 | 0:07
💻 | MacBook Pro </br>Retina, 15", Mid 2015 | 2.5 GHz i7 | 16 GB | 0:42 | 0:09
💻 | MacBook Pro </br>Retina, 15", Mid 2015 | 2.8 GHz i7 | 16 GB | 0:39 | 0:07
![](assets/mini.jpg) | Mac Mini </br> Mid 2012, 512 SSD | 2.3GHz Quad-Core i7 | 16GB | 0:50 | 0:09
🖥 | iMac </br>HDD 500 GB, 21.5", Mid 2010 | 3.06 GHz i3 | 12 GB | 3:59 | 0:14
🖥 | iMac </br>HDD 1 TB, 21.5", Late 2012 | 2.7 GHz i5 | 8 GB | 4:15 | 0:33
🖥 | iMac </br>HDD 1 TB, 27", Late 2012 | 3.4 GHz i7 | 8 GB | 0:54 | 0:12
🖥 | iMac 5K </br>512GB Flash, 27", Late 2015 | 4.0Ghz i7 | 32 GB | 0:28 | 0:06|
![](assets/pro.jpg) | Mac Pro Flash Storage, Late 2013 | 3.5 GHz 6-Core Xeon E5 | 32 GB | 0:30 | 0:05




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
