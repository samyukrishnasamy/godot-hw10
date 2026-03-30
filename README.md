# Godot Homework – Buttons & Signals

## Homework Scene One
- Connected the button to Sonic  
- Added `_on_button_pressed()` to rotate Sonic  

## Homework Scene Two
- Used `Area2D.body_entered` to trigger rotation  
- Added function to start rotating when Godotbot enters  
- Made sure to use body signal (since Godotbot is a CharacterBody2D)  

## Homework Scene Three
- Start rotating when entering the area  
- Stop rotating when leaving the area  
- Added `_on_area_2d_body_exited()`  
- Used a boolean (`is_rotating`) to control behavior  

## Homework Scene Four
- Added a `CloseDoorButton`  
- Added an `Area2D` for detecting when Godotbot is near the door  
- Connected signals for:
  - entering area → open door  
  - leaving area → close door  
  - open button → open door  
  - close button → close door  
- Used `ShowHide` script to show and hide the door  
- Used `CollisionController` to enable and disable collision  
- Attached scripts to the correct nodes
