#Constellation.js

    We had the sky up there, and we used to lay on our backs and look up at them, and discuss whether they was made or just happened. 
    — Mark Twain

    The contemplation of celestial things will make a man both speak and think more sublimely and magnificently when he descends to human affairs. 
    — Cicero


Constellation is a simple JavaScript plugin that can draw beautiful HTML5 Canvas backgrounds, resembling star constellations. [A demo is available here](https://ngr900.github.io/constellation/).

#Usage

There are 6 different constructors you can use. The first argument is always the target element ID.

    constellation(elementID)

Uses the default preset.

    constellationPreset(elementID,presetName)

Uses the specified preset; you can view all included presets in the demo

    constellationHue(elementID,hue)

Uses the default preset with specified hue for both back and foreground.

    constellationHSL(elementID,bhue,bsat,blig,fhue,fsat,flig)

Uses the default preset with specified full HSL colors for both back and foreground.

    constellationFull(elementID,starDensity,starRadius,starRadiusJitter,starVelocity,starVelocityJitter,connectionRadius,connectionWidth,connectionOpacity,revealRadius,backgroundHue,backgroundSaturation,backgroundLightness,foregroundHue,foregroundSaturation,foregroundLightness,foregroundHueJitter,foregroundSaturationJitter,foregroundLightnessJitter,responsive)

Uses all the specified parameters.
