# ImageDemon
A proof-of-concept ImageMagick based research malware targeting images

## Overview
ImageDemon is a Batch/AutoHotkey script designed to "infect" images through convert.exe and mogrify.exe.

It will apply dithering to any images it can find (as well as applying monochrome or 4-color index color), while leaving all binary executables intact.

This will not actually infect anything else -- it just targets images.

## TODOs
1. Clean up code
2. Bugtesting
3. Make it sure this will not fuck with anything else
4. PoC code upload

## Other things
So Capcom.sys (unpatched) has a vulnerability which grants system level access to any program in specific conditions.

I want to try that exploit once I have a chance -- not particularly on this repo but something else.
