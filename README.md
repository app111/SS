# SS
modify Sine Pro and add location picker feature with which you can check-in remotely(wherever you want) in Sine Pro.
![image](https://github.com/iOS-mamu/SS/blob/master/SIne-Pro.gif)

something I learn from disassemly code:



1.core function is [SCSite sitesForLocation:(SCLocation *)location distance:(double)distance block:(id)block] to fetch avaible sites near your location.

2.SCSite,SCPass etc is defined in SineCommon.framework.
