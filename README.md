HGX gear extruder for archetyoe toolhead

![Alt text](/images/image.png)
![Alt text](/images/IMG_20250217_110813.jpg)

When printing you will need to split the part. Orca and Bambu slicer have this function if you right click.

klipper config info
[extruder]
rotation_distance: 53.494165  # Re-calibrate your own value
gear_ratio: 44:10, 37:17

direction pin should not need to be flipped

Gears used https://www.aliexpress.com/item/1005004699143725.html?spm=a2g0o.order_list.order_list_main.5.4e4f1802knTc39

Inspired by https://github.com/odbee/shepherd
and
https://github.com/nhchiu/VoronMods/tree/main/Extruders/Hummingbird
