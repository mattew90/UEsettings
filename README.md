Collection of ini settings that can help performance and/or visuals. Seems to work in unreal engine 5 and 4 but some settings are different or were not added yet. Settings were benchmarked and source code was referenced to confirm settings still have an effect. Even so these settings can be unstable or have issues so use what you need. Some settings also depend on the capabilities of your hardware so confirm compatibility. I hope these settings can help you extract more from your hardware in unreal engine.

Results:

Unreal Engine 5:
Volumetric clouds have a noticeable performance impact but also affects visuals if games rely on it.

1440p with volumetric clouds at 2560x1440 went from ~214fps or 4.5ms to ~344 fps or 2.8ms. 
1440p without volumetric clouds went from ~351fps or ~2.8ms to ~380 fps or 2.5ms so still engine limited there but if gpu limited performance should improve.  
5K with volumetric clouds at 2560x1440 supersampled to 5120x2880 by using r.screenpercentage 200 went from ~80fps or ~12.5ms to ~175 fps or ~5.8ms. 
5K without volumetric clouds went from ~120fps or ~8.4ms to ~325fps or ~3.0ms.

Also tested on a laptop and made a game go from 4k ~30fps to above 60fps. Around ~80fps if I remember. But even if the framerates appear high from my results in a basic level, in actual games the performance will obviously be different but should be faster than the default settings.


Unreal Engine 4: 
1440p at 2560x1440 went from ~450fps or ~2.2ms to ~750fps or ~1.3ms
1440p at 2560x1440 supersampled to 5120x2800 by using r.screenpercentage 200 went from ~140fps or ~7.0ms to ~300fps or ~3.5ms.
