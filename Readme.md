Xcode Hardware Performance
==========================

These are the results from running Xcode on a non-trivial open source project using various Macs. The goal is to give developers a relative idea of how each computer model compares to one another. Read the [specifics](#specifications) and [contributing](#contributing) sections for more info.

Xcode 10
-------

🖥 | Computer Model | CPU | RAM | Fresh Build Time | Incremental Build Time | Xcode Version | Date & Commit Hash | New Build System? |
-- | -------------- | --- | --- | ---------------- | ---------------------- | ---- | ---- | ----------------- |
💻 | MacBook Pro <br />Retina, 15", Mid 2015 | 2.5 GHz i7-4870HQ | 16 GB | 0:46 | 0:10 | 10.1 | 2019-03-03 ([commit](https://github.com/artsy/eidolon/commit/5d08938cf325c91f0121acfdb11b1de12ddf1b45)) | :heavy_check_mark:
💻 | MacBook Pro <br />Retina, 15", Mid 2018 | 2,6 GHz i7-8850H | 16 GB | 0:28 | 0:09 | 10.1 | 2019-01-12 ([commit](https://github.com/artsy/eidolon/commit/c4e042680c8cea809b42eb2b1c827a3ea1d780b4)) | :heavy_check_mark:
⌨️ | [Custom PC](https://github.com/ashfurrow/xcode-hardware-performance/pull/90)| 4.0 GHz i7-8086K | 32 GB | 0:31 | 0:11 | 10.1 | 2019-01-10 ([commit](https://github.com/artsy/eidolon/commit/5d08938cf325c91f0121acfdb11b1de12ddf1b45)) | :heavy_check_mark:
![](assets/pro.png) | Mac Pro <br />Flash Storage, Late 2013 | 2.7 GHz 12-Core Xeon E5 | 64 GB | 0:40 | 0:08 | 10.1 | 2018-12-15 ([commit](https://github.com/artsy/eidolon/commit/5d08938cf325c91f0121acfdb11b1de12ddf1b45)) | :heavy_check_mark:
![](assets/mini.png) | Mac Mini, <br /> Late 2012 | 2.3 GHz i7-3615QM | 8 GB | 1:05 | 0:14 | 10.1 | 2018-11-15 ([commit](https://github.com/artsy/eidolon/commit/c4e042680c8cea809b42eb2b1c827a3ea1d780b4)) | :heavy_check_mark:
💻 | MacBook Pro <br />Retina, 15", Mid 2014 | 2.8 GHz i7-4980HQ | 16 GB | 0:49 | 0:09 | 10.1 | 2018-11-16 ([commit](https://github.com/artsy/eidolon/commit/c4e042680c8cea809b42eb2b1c827a3ea1d780b4)) | :heavy_check_mark:
💻 | MacBook Pro <br />Non-Retina, 13", Mid 2012, <br />180 GB SSD | 2.5 GHz i5-3210M | 16 GB | 2:35 | 0:17 | 10.1 | 2018-11-16 ([commit](https://github.com/artsy/eidolon/commit/c4e042680c8cea809b42eb2b1c827a3ea1d780b4)) | :heavy_check_mark:
![](assets/mini-2018.png) | Mac Mini, <br /> Late 2018, 512GB SSD | 3.2 GHz i7-8700B | 16 GB | 0:32 | 0:07 | 10.1 | 2018-11-15 ([commit](https://github.com/artsy/eidolon/commit/c4e042680c8cea809b42eb2b1c827a3ea1d780b4)) | :heavy_check_mark:
![](assets/mini-2018.png) | Mac Mini, <br /> Late 2018, 256GB SSD | 3.0 GHz i5-8500B | 8 GB | 0:42 | 0:08 | 10.1 | 2018-11-15 ([commit](https://github.com/artsy/eidolon/commit/c4e042680c8cea809b42eb2b1c827a3ea1d780b4)) | :heavy_check_mark:
💻 | MacBook Pro <br />Retina, 15", Mid 2018 | 2.2 GHz i7-8750H | 16 GB | 0:35 | 0:08 | 10.1 | 2018-11-16 ([commit](https://github.com/artsy/eidolon/commit/c4e042680c8cea809b42eb2b1c827a3ea1d780b4)) | :heavy_check_mark:
⌨️ | [Custom PC](https://github.com/ashfurrow/xcode-hardware-performance/pull/81)| i9-9900K 4.8 GHz | 32 GB | 0:25 | 0:07 | 10.1 |2018-11-04 | :heavy_check_mark:
💻 | MacBook Pro <br />Retina, 15", Mid 2012 | 2.6 GHz i7-3720QM | 16 GB | 0:40 | 0:042 | 10.0 | 2018-09-13 ([commit](https://github.com/michael-mckenna/xcode-hardware-performance/commit/cc869fd91cc731789fb1aab14de81e13b4718172)) | :heavy_check_mark:
💻 | MacBook Pro <br />Retina, 15", Mid 2015 | 2.8 GHz i7-4980HQ | 16 GB | 0:36 | 0:038 | 10.0 | 2018-09-24 ([commit](https://github.com/GDXRepo/xcode-hardware-performance/commit/e7ccab80a3cd3451e444b03ada3495f674af84f1)) | :heavy_check_mark:
💻 | MacBook Air <br />13", Mid 2017 | 1.8 GHz i5-5350U | 8 GB | 1:47 | 0:15 | 10.0 | 2018-10-01 ([commit](https://github.com/artsy/eidolon/commit/e90a1ffd38d73179a6fe2174587dcd98988efc48)) | :heavy_check_mark:

Xcode 9
-------

🖥 | Computer Model | CPU | RAM | Fresh Build Time | Incremental Build Time | Xcode Version | Date & Commit Hash | New Build System? |
-- | -------------- | --- | --- | ---------------- | ---------------------- | ---- | ---- | ----------------- |
💻 | MacBook Pro <br />Retina, 15", Mid 2018 | 2.2 GHz i7 | 32 GB | 0:42 | 0:09 |  | 2018-05-19 ([commit](https://github.com/artsy/eidolon/commit/e90a1ffd38d73179a6fe2174587dcd98988efc48)) | :heavy_check_mark:
💻 | MacBook Pro <br />Retina, 15", 2018 | 2.9 GHz i9 | 32 GB | 0:30 | 0:04 |  | 2018-05-19 ([commit](https://github.com/artsy/eidolon/commit/e90a1ffd38d73179a6fe2174587dcd98988efc48)) | :heavy_check_mark:
💻 | MacBook Pro <br />Retina, 13", Early 2015 | 2.7 GHz i5 | 8 GB | 2:25 | 0:31 |  | 2018-05-19 ([commit](https://github.com/artsy/eidolon/commit/e90a1ffd38d73179a6fe2174587dcd98988efc48)) | :x:
💻 | MacBook Pro <br />Retina, 13", Early 2015 | 2.7 GHz i5 | 8 GB | 1:12 | 0:18 |  | 2018-05-19 ([commit](https://github.com/artsy/eidolon/commit/e90a1ffd38d73179a6fe2174587dcd98988efc48)) | :heavy_check_mark:
💻 | MacBook Pro <br />Retina, 15", Mid 2018 | 2.9 GHz i9 | 32 GB | 0:32 | 0:04 |  | 2018-05-19 ([commit](https://github.com/artsy/eidolon/commit/e90a1ffd38d73179a6fe2174587dcd98988efc48)) | :heavy_check_mark:
⌨️ | [Custom PC](https://github.com/ashfurrow/xcode-hardware-performance/pull/62)<br />Early 2018 | i7-8700K 4.70+ GHz | 32 GB | 0:19 | 0:07 |    | 2018-03-11 ([commit](https://github.com/artsy/eidolon/commit/0bd0899bab780b2938489cd0abd64e07e229672a)) | :heavy_check_mark:
⌨️ | [Custom PC](https://github.com/ashfurrow/xcode-hardware-performance/pull/73)<br />Early 2016 | i7-6700k 4.5 GHz | 32 GB | 0:23 | 0:07 | 9.4.1 | 2018-05-19 ([commit](https://github.com/artsy/eidolon/commit/e90a1ffd38d73179a6fe2174587dcd98988efc48)) | :heavy_check_mark:
💻 | [MacBook Pro](https://github.com/ashfurrow/xcode-hardware-performance/pull/73) <br />Retina, 13", Mid 2018 | 2.7 GHz i7-8559U | 16 GB | 0:27 | 0:09 | 9.4.1 | 2018-05-19 ([commit](https://github.com/artsy/eidolon/commit/e90a1ffd38d73179a6fe2174587dcd98988efc48)) | :heavy_check_mark:
⌨️ | [Custom PC](https://github.com/ashfurrow/xcode-hardware-performance/pull/61)<br />Early 2018 | i7-7700k 4.5 GHz | 16 GB | 0:35 | 0:05 |    | 2018-03-10 | :heavy_check_mark:
⌨️ | [Custom PC](https://github.com/ashfurrow/xcode-hardware-performance/pull/57)<br />Early 2018 | i7-8700K 4.70+ GHz | 32 GB | 0:36 | 0:07 |    | 2018-02-19 ([commit](https://github.com/artsy/eidolon/commit/0bd0899bab780b2938489cd0abd64e07e229672a)) | :x:
⌨️ | [Custom PC](https://github.com/ashfurrow/xcode-hardware-performance/pull/61)<br />Early 2018 | i7-7700k 4.5 GHz | 16 GB | 0:48 | 0:07 |    | 2018-03-10 | :x:
⌨️ | [Custom PC](https://github.com/ashfurrow/xcode-hardware-performance/pull/58)<br />Late 2015 | i7-4790k 4.0 GHz | 32 GB | 0:40 | 0:07 |    | 2018-02-22 ([commit](https://github.com/artsy/eidolon/commit/0bd0899bab780b2938489cd0abd64e07e229672a)) | :x:
🖥 | iMac Pro <br />10 Core, Late 2017 | 3 GHz Intel Xeon W | 64 GB | 0:41 | 0:07 |    | 2017-12-28 | :x:
🖥 | iMac Pro <br />18 Core, Late 2017 | 2.3 GHz Intel Xeon W | 128 GB | 0:47 | 0:07 |    | 2018-03-07 ([commit](https://github.com/artsy/eidolon/commit/24c721af3a9991c7c1ebd5dcaef80f470cf5ddcc)) | :x:
🖥 | iMac 27" <br />5K 1TB SSD, Mid 2017 | 4,2 GHz i7 | 40 GB | 0:49 | 0:08 |    | 2018-01-18 | :x:
💻 | MacBook Pro <br />Retina, 15", 2017 | 2.9 GHz i7 | 16 GB | 0:49 | 0:16 |    | 2017-10-09 | :heavy_check_mark:
💻 | MacBook Pro <br />Retina, 15", 2017 | 2.9 GHz i7 | 16 GB | 0:50 | 0:15 |    | 2017-10-09 | :x:
💻 | MacBook Pro <br />Retina, 15", 2016 | 2.9 GHz i7 | 16 GB | 1:04 | 0:09 | 9.4.1 | 2018-07-18 ([commit](https://github.com/artsy/eidolon/commit/e90a1ffd38d73179a6fe2174587dcd98988efc48)) | :heavy_check_mark:
💻 | MacBook Pro <br />Retina, 15", 2016 | 2.9 GHz i7 | 16 GB | 1:06 | 0:10 | 9.4.1 | 2018-07-18 ([commit](https://github.com/artsy/eidolon/commit/e90a1ffd38d73179a6fe2174587dcd98988efc48)) | :x:
💻 | MacBook Pro <br />Retina, 15", 2015 | 2.5 GHz i7 | 16 GB | 0:51 | 0:09 | 9.2 | 2018-03-02 ([commit](https://github.com/artsy/eidolon/commit/e98923f54a3fee3642051b9f48556c5e912591e0)) | :heavy_check_mark:
🖥 | MacPro Late 2013 | 2.7 GHz 12core Intel Xeon E5 | 64 GB | 0:54 | 0:10 |    | 2018-03-07 ([commit](https://github.com/artsy/eidolon/commit/24c721af3a9991c7c1ebd5dcaef80f470cf5ddcc)) | :x:
🖥 | iMac 27"<br />256GB SSD, Late 2013 | 3.2 GHz i5 | 24 GB | 0:56 | 0:10 | 9.2 | 2018-03-02 ([commit](https://github.com/artsy/eidolon/commit/e98923f54a3fee3642051b9f48556c5e912591e0)) | :heavy_check_mark:
💻 | [MacBook Pro](https://github.com/ashfurrow/xcode-hardware-performance/pull/73) <br />Retina, 15", Mid 2012 | 2.6 GHz i7-3720QM | 16 GB | 1:04 | 0:13 | 9.4.1 | 2018-05-19 ([commit](https://github.com/artsy/eidolon/commit/e90a1ffd38d73179a6fe2174587dcd98988efc48)) | :heavy_check_mark:
💻 | MacBook Pro <br />Retina, 15", Late 2013 | 2.6 GHz i7 | 16 GB | 1:09 | 0:12 |    | 2018-02-28 | :heavy_check_mark:
💻 | MacBook Pro <br />Retina, 15", 2015 | 2.8 GHz i7 | 16 GB | 1:17 | 0:12 |    | 2018-01-02 | :x:
💻 | MacBook Pro <br />Retina, 15", 2015 | 2.5 GHz i7 | 16 GB | 1:20 | 0:09 | 9.2 | 2018-03-02 ([commit](https://github.com/artsy/eidolon/commit/e98923f54a3fee3642051b9f48556c5e912591e0)) | :x:
🖥 | iMac 27"<br />256GB SSD, Late 2013 | 3.2 GHz i5 | 24 GB | 1:27 | 0:10 | 9.2 | 2018-03-02 ([commit](https://github.com/artsy/eidolon/commit/e98923f54a3fee3642051b9f48556c5e912591e0)) | :x:
⌨️ | [Custom Laptop](https://github.com/ashfurrow/xcode-hardware-performance/pull/67)<br />Mid 2018 | i5-8250u 3.4 GHz | 16 GB | 1:58 | 0:10 | 9.3 | 2018-05-11 | :x:
💻 | MacBook Pro <br />Retina, 13", 2014 | 2.6 GHz i5 | 8 GB | 2:30 | 0:23 |    | 2018-01-04 | :x:
![](assets/mini.png) | Mac Mini <br /> Mid 2012, 512 SSD | 2.3 GHz Quad-Core i7 | 16 GB | 1:32 | 0:18 |    | 2017-10-20 | :x:
💻 | MacBook Pro <br />Retina, 15", 2017 | 2.8 GHz i7 | 16 GB | 1:50 | 0:14 |    | | :x:
🖥 | iMac 27" <br />120GB SSD, Mid 2010 | 2.93 GHz i7 | 8 GB | 2:05 | 0:16 | 9.3 | 2018-03-21 | :x:
💻 | MacBook <br />Retina, 15", Mid 2012 | 2.6 GHz i7 | 8 GB | 2:26 | 0:23 |    | | :x:
💻 | MacBook Pro <br />13", Mid 2012 | 2.9 GHz i7 | 8 GB | 2:30 | 0:23 |    | | :x:
![](assets/pro.png) | Mac Pro <br />Flash Storage, Late 2013 | 3.7 GHz 4-Core Xeon E5 | 32 GB | 1:15 | 0:10 | 9.4.1 | 2018-06-20 ([commit](https://github.com/artsy/eidolon/commit/e90a1ffd38d73179a6fe2174587dcd98988efc48)) | :x:
![](assets/pro.png) | Mac Pro <br />Flash Storage, Late 2013 | 3.7 GHz 4-Core Xeon E5 | 32 GB | 0:35 | 0:11 | 9.4.1 | 2018-06-20 ([commit](https://github.com/artsy/eidolon/commit/e90a1ffd38d73179a6fe2174587dcd98988efc48)) | :heavy_check_mark:
💻 | MacBook Pro <br />13", Mid-2017, 256GB SSD | 2.3 GHz i5 (I5-7360U) | 8 GB | 01:42 | 0:12 | 9.2 | 2018-06-29 | :x:
💻 | MacBook Pro <br />13", Mid-2017, 256GB SSD | 2.3 GHz i5 (I5-7360U) | 8 GB | 01:12 | 0:12 | 9.2 | 2018-06-29 | :heavy_check_mark:
![](assets/mini.png) | Mac Mini, <br /> Mid-2011, 128GB SSD | 2.3 GHz i5 (I5-2415M) | 8 GB | 03:12 | 0:20 |  9.2 | 2018-07-04 | :x:
![](assets/mini.png) | Mac Mini, <br /> Mid-2011, 128GB SSD | 2.3 GHz i5 (I5-2415M) | 8 GB | 02:04 | 0:20 |  9.2 | 2018-07-04 | :heavy_check_mark:

Xcode 8
-------

🖥 | Computer Model | CPU | RAM | Fresh Build Time | Incremental Build Time | Date |
-- | ------------- | --- | --- | ---------------- | ---------------------- | ---- |
🖥 | iMac 5K <br />512GB Flash, 27", Late 2015 | 4.0 GHz i7 | 32 GB | 0:28 | 0:06| |
![](assets/pro.png) | Mac Pro <br />Flash Storage, Late 2013 | 3.5 GHz 6-Core Xeon E5 | 32 GB | 0:30 | 0:05 |
💻 | MacBook Pro <br />Retina, 15", Mid 2015 | 2.8 GHz i7 | 16 GB | 0:39 | 0:07 |
💻 | MacBook Pro <br />Retina, 15", Mid 2015 | 2.5 GHz i7 | 16 GB | 0:42 | 0:09 |
💻 | MacBook Pro <br />Retina, 15", Mid 2012 | 2.3 GHz i7 | 16 GB | 0:46 | 0:08 |
💻 | MacBook Pro <br />Retina, 15", Early 2013 | 2.4 GHz i7 | 8 GB | 0:47 | 0:10 |
![](assets/mini.png) | Mac Mini <br /> Mid 2012, 512 SSD | 2.3GHz Quad-Core i7 | 16GB | 0:50 | 0:09 |
💻 | MacBook Pro <br />Retina, 15", Mid 2014 | 2.2 GHz i7 | 16 GB | 0:51 | 0:07 |
💻 | MacBook Pro <br />Retina, 15", Late 2013 | 2.3 GHz i7 | 16 GB | 0:53 | 0:09 |
🖥 | iMac <br />HDD 1 TB, 27", Late 2012 | 3.4 GHz i7 | 8 GB | 0:54 | 0:12 |
💻 | MacBook Pro <br />Touch Bar, 15", Late 2016 | 2.9 GHz i7 | 16 GB | 0:54 | 0:17 |
💻 | MacBook Pro <br />15", Early 2011 | 2.0 GHz i7 | 8 GB | 1:00 | 0:13 |
💻 | MacBook Pro <br />15" Early 2011, SSD | 2.0 GHz i7 | 8 GB | 1:01 | 0:10 |
💻 | MacBook Pro <br />Touch Bar, 15", Late 2016 | 2.9 GHz i7 | 16 GB | 1:04 | 0:26 |
💻 | MacBook Pro <br />13", Early 2015, 1TB SSD | 3.1 Ghz i7 | 16 GB | 1:25 | 0:09 |
💻 | MacBook Pro <br />Retina, 13", Early 2015 | 2.7 GHz i5 | 8 GB | 1:35 | 0:11 |
💻 | MacBook <br />Retina, 12", Mid 2017 | 1.4 GHz i7 | 16 GB | 1:49 | 0:16 |
💻 | MacBook Pro <br />13", Mid 2012 256 SSD | 2.5 GHz i5 | 8 GB | 2:08 | 0:19 |
💻 | MacBook Air <br />13", Mid 2012, 512 SSD | 2 Ghz i7 | 8 GB | 2:10 | 0:11 |
💻 | MacBook <br />Retina, 12", Early 2016 | 1.2 GHz m5 | 8 GB | 2:10 | 0:12 |
💻 | MacBook Pro <br />13", Late 2013 256 SSD | 2.4 GHz i5 | 8 GB | 2:17 | 0:23 |
💻 | MacBook <br />Retina, 12", Early 2015 | 1.2 GHz M | 8 GB | 2:28 | 0:12 |
💻 | MacBook <br />Retina, 12", Early 2015 | 1.1 GHz M | 8 GB | 3:00 | 0:12 |
💻 | MacBook Pro <br />13", Early 2011, 512 SSD | 2.7 Ghz i7 | 8 GB | 2:30 | 0:16 |
💻 | MacBook Air <br />13", Mid 2013, 128 SSD | 1.3 Ghz i5 | 4 GB | 2:58 | 0:24 |
💻 | MacBook Pro <br />13", Mid 2010 512 SSD | 2.4 GHz Intel Core 2 Duo | 8 GB | 3:01 | 0:24 |
🖥 | iMac <br />HDD 500 GB, 21.5", Mid 2010 | 3.06 GHz i3 | 12 GB | 3:59 | 0:14 |
🖥 | iMac <br />HDD 1 TB, 21.5", Late 2012 | 2.7 GHz i5 | 8 GB | 4:15 | 0:33 |

Specifications
--------------

For the test, I decided to use an app that I actually work on: [eidolon](https://github.com/artsy/eidolon). Unlike most iOS apps, the project is stable and not under active development, so it's a prime candidate for accurate-ish benchmarking.

For "fresh" builds, I cleaned the build folder (⌘⇧K) repeatedly until it worked with no permissions problems. Then I sat and waited for Xcode to index the project. I also made sure the simulator was _closed_, so these times include booting the simulator and launching the app. Then I hit ⌘R and start a timer, only ending it when the app had fully launched.

"Incremental" builds represent a more common use case: changing one file and recompiling with the simulator already running. I added `print("hello!")` to `application(: didFinishLaunchingWithOptions:)` and hit ⌘R, timing the time it took for the app to launch.

I repeated each test a few times and took their average times.

Contributing
------------

It would be super-cool if we could perform the above tests on a variety of machines and consolidate the results here. You can [follow the instructions](https://github.com/artsy/eidolon#downloading-the-code) to download the code and the project dependencies, and send a pull request adding your own results. I'd super-appreciate it! :bow:

Please note that this project is released with a Contributor Code of Conduct. By participating in this project, you agree to abide by [its terms](Code%20of%20Conduct.md).

License
-------

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
