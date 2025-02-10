# Prusa Slicer Profile for Anycubic Kobra 2 Pro

## Description

When I bought the Kobra 2Pro the AC Slicer Next was still a dream in someone's head, and even when the Anycubic slicer came out it was still a "dog shit" to be considered as a slicer. So Anycubic were shipping the Prusa Slicer .exe file on the USB that came with the printer.

And that's why my main slicer was the Prusa Slicer for that time, and to get the most of my printer and enhance its quality, I had to adjust and tune the print profiles to get the results I always wanted. Obviously, I wasn't able to achieve that.

Until a couple months ago, when I got down the rabbit hole of tuning, tweaking, and upgrading my 3D printer, and just "wasted" a couple of rolls of filament to get the most out of my printer.  

But I am glad to announce that, all my effort didn't go down the sink, and finally I have a perfect profile to use on Prusa Slicer along with my Kobra 2Pro.

## Results

Here I published some of the print results I was able to get using it, but you can find more about it on [Printables](https://www.printables.com/model/710525-updated-my-prusa-slicer-profile-for-anycubic-kobra), Makeronline or MakerWorld, hop on to the folder named Results to see more of the print results.

[Photos and videos will be added here]

The pictures show some impressive results that I got using this print profile on the AC Kobra 2 Pro. I tried to do my worst to capture every single flaw on them but had to do my best to just try and capture anything since the white filament doesn't appear clearly on the phone camera.

## What's New?

PETG was added, but it is still in beta. Remember to choose it in the Filament and Process menu.

[Image will be added here]

## How to Setup?

The importing process of print profiles on Prusa Slicer could be a bit overwhelming specially for someone who just started. So I made this video about how to install Prusa Slicer and Import my print profiles for The Kobra 2 Pro:

https://youtu.be/340GGacIlzQ

## Afterword Adjusting

Although the Slicer is doing most of the work, you would need to adjust a couple of settings from the printer itself, such as the z-offset.

### Z-offset Adjustment

Use the one layer test model to adjust the z-offset value.

To do that start printing the test model then try to adjust the z-offset value from the printer screen, until you get good and consistent results.

### Important Note

> You would need to perform the first layer test and adjust the z offset every time you use auto leveling

- Send it higher if the first layer is a bit squished to the build plate
[Photo will be added here]

- Send it down if the lines of the first layer are separate or if it doesn't stick at all
[Photo will be added here]

### What We Are Looking For on the First Layer?

The perfect first layer should look something like this:
[Photo will be added here]

The lines that form the first layer should be attached together with no spaces between them, and the edges should not form a wiggly line instead it should be sharp with no distortion.

The first layer is a bit difficult to achieve perfectly, since it can be affected by multiple factors such as the build plate quality, or if the printer is damaged, or incorrect z-axis alignment.

In that case you would need to do some serious work to adjust the hardware itself.

### Calibration

I would recommend doing a series of calibration from your 3D printer settings before doing the first layer test (just to make sure that there are no other problems interfering with the test).

## Iteration

Normally, I start with the template provided by the 3D printer, or the filament manufacturer, then build upon it and enhance it till we get a result that I am satisfied with.

And from the results I got, the difference is like night and day, it's a huge step up from the result that you would get with default printing profile.

[Photo with the 3 different results will be added here]
[Photo with all the tower tests will be added here]

### Testing Models

The models I used varies from ones that I got from across the internet, others provided by the slicer itself, such as Orca Slicer or Anycubic Slicer Next, and others that I designed myself.

Basically I try to print a generic model, (one of my previous projects, or a generic test model), then I observe any defects or flaws that appear on the results. I take note, and try to assume what could be causing that, adjust the print settings and try again, until we get satisfying results.

## Important Notes

1. This print profile should be considered as a template, and that means you should not rely on it for all your 3D prints, sometimes you should tune it a little bit to suit your model.

2. One of the settings that bothered me a lot, is Z-Hop. It is essential to have a smooth top surface and minimize the noise during printing, but it ruins the print most of the time.

   However, I did tune it, so we can get the most out of it. But you may consider turning it off and every other setting related to it, in case you noticed your printing started to suck.

3. What is important is you shouldn't rely on the Z-offset given by auto bed leveling, sometimes it could be wrong and end up damaging the bed.
