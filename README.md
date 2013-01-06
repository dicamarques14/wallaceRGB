wallaceRGB
==========

This is a swing based java utility to control rgb lights via serial communication (namely arduino based projects but it could be modified for commercial lights using rs232 serial)

Inspired by this project: http://www.makeuseof.com/tag/build-your-own-dynamic-ambient-lighting-for-a-media-center/ , wallaceRGB was made to be a permanent, flexible utility for controlling LED RGB lights.

GENERAL FEATURES:
--------------

    - Switch Serial/COM ports
    - Minimize to the system tray
    - Toggle lights on and off (included in system tray)
    - (soon) Choose mode from the system tray

MODES:
--------------

    - AMBIENT LIGHTING
        - (coming very soon) Adjust brightness
        - Change screen-shot capture rate
        - Change number of pixels between each analysis
        - (coming soon) scan the edge of the screen only

    - MANUAL COLOR
        - (coming very soon) Adjust brightness
        - Keep the currently showing color
        - Pick a color from swings great color picker.
        - Preview colors in the color palette, cancel button will return to the color show before the preview.
    
    - PRESET SEQUENCES
        - (coming very soon) Choose from a list of preset sequences.
        - Adjust the preset sequences interval and fade settings.
    
    - CUSTOM SEQUENCES (a long way away)
        - choose as many colors as you want
        - set individual intervals
        - set individual fade


KNOWN ISSUES:
--------------

        - Stack overflow bug during sequences


