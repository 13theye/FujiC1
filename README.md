# FujiC1
Capture One Styles replicating Fuji in-camera color. These were developed over hours of painstaking matching over many files, then cross-checked and adjusted again. That said, I'm sure there is still room for improvement!

These effects, combined with the film sim and white balance info that the camera attaches to the RAW file, enable you to get very close to custom recipes saved on-camera.

# Note:
I am not a color professional, so please be nice.
This was not done on a professionally calibrated monitor, but on a 2024 Macbook Pro with TrueTone and Night Shift turned off.

# Version 0.2:
Changes:
- Luma masks added. Each style contains layer(s) that are controlled by luma masks. The effect is now much more accurate.
- Color Chrome has the "Color Chrome (high luma)" layer added. This preserves perceived dynamic range and color brightness in specific situations.
- Color Chrome Blue better reproduces the effect on highly saturated sky colors and strong artificial light like green/blue neon and LED.
- Skin Tones.costyle is deleted. The above changes make it redundant.


# Version 0.1:
# Color Chrome
Replicating the in-camera setting of the same name. Darkens red, green, and yellow tones and adjusts their saturation and hue. Different tones are subject to varied impact on midtones or highlights.

# Color Chrome Blue
Replicating Color Chrome FX Blue. Works only on blues and I've found it to be a much stronger effect. Doesn't touch saturation much but significantly darkens. Quite a bit of hue shift toward a more "vintage" vibe.

# Skin Tones
Not a Fuji setting per se but I've found that this helps make skin tones more natural if the Color Chrome effects are heavily used. Mostly matches how it looks in-camera, just a bit less saturated.

# Instructions
These styles apply settings from the Color Editor - Advanced onto an Adjustment Layer. At 100%, this corresponds to the "Strong" setting in-camera. You can combine these layers into your own Custom Style in order to easily combine them to varying degrees.
