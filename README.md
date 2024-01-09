# MauiEmptyCollectionCpuIssue
Reproduction of Empty CollectionView CPU issue when scrolling.

To reproduce:
1. Launch the app
2. Monitor CPU usage using `adb shell top`
3. Scroll on the blank screen for 10 seconds, (I find it easiest to do a drag on the screen in a circular pattern)
4. Stop scrolling and check if the CPU usage stays high, if no go back to 3

Usually after 1-2 attempts the CPU stays high (40-50%) even when not scrolling. After some time the phone gets hot.
