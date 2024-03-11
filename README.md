# GUI_AutoTH_QuPath

This script creates a GUI in which the user can choose the setings to apply different Auto-threshold methods for segmentation.
The script list the channels for Fluorescence, H&E and H-DAB images. Tooltips appear for each of the fields

This discussion about Auto-Threshold started here: https://forum.image.sc/t/applying-automatic-threshold-method-in-qupath/88287

@yau-lim (2023) did the original core funcionality of the Auto-Threshold in this script: https://gist.github.com/yau-lim/3ed5ae04e82e02939b419afc11dc918c
All the credits for @yau-lim, I just added a few functions and the GUI.

Regarding the running options, I got the inspiration from the amazing extension Segment Anything Extension from @ksugawara. 
I use the SAM extension a LOT. This is just an alternative, since Auto-Thresholds can do a really good job for some segmentation tasks.

The inspiration to do the GUI was the "Create thresholder" pane into QuPath. The idea was to make it familiar to the user. 
 I used as reference the script from @PeteBankhead https://gist.github.com/petebankhead/486690d13912f6a95bb0489458df959e
 Due some libs, I guess that the script just works for QuPath versions 0.5 or avobe.

Perhaps some imports are not essential. For sure the code could be shorter, but It is my first GUI and at least it works :D (I hope)

@author Isaac Vieco-Martí (2024)
