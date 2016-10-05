OTF exported from `VarelaRound-Regular.glyphs` with Glyphs 2.3 with Remove Overlap and Autohinting enabled.

TTF exported from `VarelaRound-Regular.glyphs` with Glyphs 2.3 with Remove Overlap but without autohinting, then hinted with ttfautohint using this command:

    ttfautohint \
     --composites \
     --default-script=latn \
     --fallback-script=hebr \
     --detailed-info \
     --verbose \
     --strong-stem-width=gGD \
     --windows-compatibility \
     --increase-x-height=0 \
     fonts/ttf/VarelaRound-Regular.ttf \
     fonts/ttf/VarelaRound-Regular-TA.ttf;
     mv fonts/ttf/VarelaRound-Regular-TA.ttf fonts/ttf/VarelaRound-Regular.ttf;
 
Note that the `increase-x-height` feature is de-activated to make hand-hinting in the future easier to do without creating visible changes.
