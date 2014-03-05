### Beginnings
Initialy looked a cairo since I've tracked it for a few years, but never have gottern around to using it.
Raj Milan also pointed out Skia, and Moz2d. This documents covers notes on those comparisons.

* Cairo

* Skia

* Moz2d (aka GFX, Azure)


### Notes on building Skia:
Im coming from OSX, so there are good docs on Google's site though the topic is still quite sparse, and some are quite old (XCode 3)

https://sites.google.com/site/skiadocs/user-documentation/quick-start-guides/mac

https://sites.google.com/site/skiadocs/developer-documentation/contributing-code/downloading

Once GYP was properly installed The SampleApp built fine, and ran. Debug and Release boths worked, 'make clean' is necessary between the two.

#### Toward a simple "hello world"

Still looking for a real simple example. Following the notes on this post

http://stackoverflow.com/questions/6639640/want-to-learn-graphics-using-skia-on-ubuntu

Its looks like there should be libskia.a built. For OSX, however, it looks like it is done slightly different. There is a hierarchy of XCode projects that end up builting about 25 *.a files.  Seven of them are part of the skia_lib.xcodeproj perhaps that set is the same. More experiemnts later.


