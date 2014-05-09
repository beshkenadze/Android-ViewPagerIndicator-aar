Android-ViewPagerIndicator-aar
========================

Paging indicator widgets compatible with the ViewPager from the Android Support Library and ActionBarSherlock. Originally based on Patrik Åkerfeldt's ViewFlow. 
http://viewpagerindicator.com

How to use
=======================
Before you can get aar you should checkout [Android-ViewPagerIndicator](https://github.com/JakeWharton/Android-ViewPagerIndicator) submodule. Overall build process including build is straightforward:
```bash
  $ git submodule update --init
  ...
  $ ./gradlew build
  ...
```

When build is finished aar file will be located in `build/libs`.

Maven artifact in local repo
======================

```bash
  $ ./gradlew build uploadArchives
```

