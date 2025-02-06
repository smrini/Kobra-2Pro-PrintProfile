# Anycubic Next Slicer Profile for Kobra 2 Pro

## Description
Anycubic Finally released their own slicer the "Anycubic Slicer Next" which is built on the Orca Slicer, specifically to control their printers, with the added ability to control and monitor the prints remotely.

Responding to the users demands, after my Prusa slicer print profile for the Anycubic Kobra 2 pro went viral, I made a new version for the newly released slicer Anycubic Slicer Next.

## Results
Here I published some of the print results I was able to get using it, but you can find more about it on Printables, Makeronline or MakerWorld, hop on GitHub to see more of the print results.

[Photos will be added here]

The pictures show some impressive results that I got using this print profile on the AC Kobra 2 Pro. I tried to do my worst to capture every single flaw on them but had to do my best to just try and capture anything since the white filament doesn't appear clearly on the phone camera.

## What's New?
PETG was added, but it is still in beta. Remember to choose it in the Filament and Process menu.

## How to Setup?
Since the importing process of printing profiles on the Anycubic Slicer Next (what a long name) is still bad and confusing, and it makes you import different files.

I decided to publish this small video that demonstrates how to install the Anycubic Slicer Next and then import the print profile to it, using an alternative way.

This is a step-by-step guide about how to install the Anycubic Slicer Next and import the print profiles:
https://youtu.be/340GGacIlzQ

I made this video in a rush, I may redo it again and add more details.

Also, instead of going to that directory manually, you can go to it by copying this path into the navigation bar on File Explorer:
```
C:\Users\%UserProfile%\AppData\Roaming\AnycubicSlicerNext\user
```

## Afterword Adjusting
Although the Slicer is doing most of the work, you would need to adjust a couple of settings from the printer itself, such as the z-height.

### Z-offset Adjustment
Use the one layer test model to adjust the z-offset value. To do that, start printing the test model then try to adjust the z-offset value from the printer screen until you get good and consistent results.

### Important Note
You would need to perform the first layer test and adjust the z offset:
- Every time you use auto leveling
- Send it higher if the first layer is a bit squished to the build plate
- Send it down if the lines of the first layer are separate or if it doesn't stick at all

### What We Are Looking For on the First Layer?
The perfect first layer should look something like this:
[Photo will be added here]

The lines that form the first layer should be attached together with no spaces between them, and the edges should not form a wiggly line; instead, it should be sharp with no distortion.

The first layer is a bit difficult to achieve perfectly since it can be affected by multiple factors such as the build plate quality, or if the printer is damaged, or incorrect z-axis alignment.

In that case, you would need to do some serious work to adjust the hardware itself.

## Calibration
I would recommend doing a series of calibrations from your 3D printer settings before doing the first layer test (just to make sure that there is no other problems interfering with the test).

## Iteration
Normally, I start with the template provided by the 3D printer or the filament manufacturer, then build upon it and enhance it until we get a result that I am satisfied with.

And from the results I got, the difference is like night and day; it's a huge step up from the result that you would get with default printing profile.

[Photos of the 3 different results will be added here]
[Photos of all the tower tests will be added here]

## Testing Models
The models I used varies from ones that I got from across the internet, others provided by the slicer itself, such as Orca Slicer or Anycubic Slicer Next, and others that I designed myself.

Basically, I try to print a generic model (one of my previous projects, or a generic test model), then I observe any defects or flaws that appear on the results. I take note and try to assume what could be causing that, adjust the print settings and try again, until we get satisfying results.
