# CIS 5660 HW03 Procedural Buildings

## Overview
In this project, I created a procedural multi-floor building generator in Houdini.

![image](https://github.com/user-attachments/assets/835ba82c-1e45-4694-a6c5-beb3d957e999)

https://github.com/user-attachments/assets/16f4439b-b282-439f-86ba-60c067301c82

Video Link: https://github.com/user-attachments/assets/16f4439b-b282-439f-86ba-60c067301c82

Since I am very new to Houdini, I was mostly sticking to the provided tutorial. Overwatch is actually my favorite game so I was very happy with the style!

### Box Stacking & Details

The first part involves creating a custom HDA that stacks buildings on top of each other. 

![image](https://github.com/user-attachments/assets/db44d44a-ac61-4e8f-8508-0018b902475b)

Then assets including procedurally created window, door and balcony models are randomly added to the walls.

|![image](https://github.com/user-attachments/assets/6f16d931-1bce-4883-bfac-66059089c343)|![image](https://github.com/user-attachments/assets/dc5feb1a-858f-4dff-baa4-406177c15929)|![image](https://github.com/user-attachments/assets/fd650a22-bfe5-43c3-b8c0-2c5782fc01b1)|![image](https://github.com/user-attachments/assets/ed4a7b45-e0cd-4408-af61-6681b0a625d5)|
|:--:|:--:|:--:|:--:|
|*Small Window*|*Large Window*|*Door*|*Balcony*|

Each asset has customizable parameters that can be controlled by the asset controller.

![image](https://github.com/user-attachments/assets/252a1080-3238-4c9f-848e-84aa5d48ef3d)

#### Small Window

Small window can be adjusted on width, height & frame width.

![Untitled video - Made with Clipchamp](https://github.com/user-attachments/assets/2e694b80-425f-4f76-8e83-7785f495e2c5)


#### Large Window

Large window can be adjusted on width, height, row & column.

![Untitled video - Made with Clipchamp (1)](https://github.com/user-attachments/assets/50b91d6e-2842-42fc-96ed-0808a46a5d35)


#### Door

Door can be adjusted on width, height & with/without knob.

![Untitled video - Made with Clipchamp (2)](https://github.com/user-attachments/assets/ed2d12aa-fd79-451c-ba71-0325f1984246)


#### Balcony

Balcony can be adjusted on width, height & rail density.

![Untitled video - Made with Clipchamp (3)](https://github.com/user-attachments/assets/7dab776b-15a6-4952-87e7-14ff6ff49b7c)


### Pillar

Pillar are then added to the building by placing boxes on the corners of each floor.

![image](https://github.com/user-attachments/assets/eb5af282-24c6-447d-845a-0897999165a5)


### Support

Finally, supports are added for floors that extend outwards.

![image](https://github.com/user-attachments/assets/fba7fc90-1029-4995-9c28-c5e71c81917a)


## Credits

- Simon Houdini's tutorial: https://www.youtube.com/watch?v=uIe97023sDk&t=979s&ab_channel=SimonHoudini
