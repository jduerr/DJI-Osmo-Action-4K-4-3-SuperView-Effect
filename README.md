# DJI Osmo Action 4K 4:3 to GoPro SuperView Effect

The DJI Osmo Action does not have a "Gopro Hero Superview" like setting. However it does give us a 4:3 aspect ratio 4K full sensor mode. 
By searching around, i found that what Gopro is doing with its super view is 
- it takes a 4:3 4K image from the sensor (like you can do with the osmo action!)
- it stretches the image from 4:3 horizontally to a 16:9 ratio (what you can do easily by applying a 133,5% transformation on the x axis in post)
- it applies some kind of an reversed fisheye effect so that the center of the image does not look as stretched as it really is. (And now you can do that in post, too by applying the effect for Final Cut Pro X i just included in this repository

## How to use
1. Just download and unpack the zip frile from this repository.
2. the folder "AV Osmo Action" into your "~/Movies/Motion Templates/Effects" folder
3. import some DJI Osmo Action footage you recorded in 4K 4:3 into an FCPX project
4. Transform the 4:3 footage to 16:9 by using "Transform X-Axis" in the inspector (133,5%)
5. Drag n drop the AV Osmo Action Super View Effect from the Effects Library onto the clip

Done !!!
