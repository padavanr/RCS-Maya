# RCS
RCS Script
![image](https://github.com/user-attachments/assets/f45cff77-da2f-47d6-964e-a4b0ec648535)

Rykov's Control Shaker – Beginner's Guide

Introduction
Rykov's Control Shaker is a tool for adding realistic shaking animation to objects in Autodesk Maya. The script offers flexible settings such as axis selection, shake modes, frame range, and baking animations to a new layer.

How to Run the Script
Save the code as RykovsControlShaker.py.
Open Script Editor in Maya.
Drag and drop the .py file into the Script Editor window.
Press Enter to run the script.
The Rykov's Control Shaker window will appear in Maya.

Interface Description
Shake Parameters 🛠️
Translation:
A slider that controls the intensity of shaking in space (object movement).
Range: 0.001 to 100.
Example:
Low values (0.01) for subtle vibrations.
High values (50–100) for strong shaking effects.
Rotation:
A slider that controls the intensity of object rotation.
Range: 0 to 360.
Example:
Use for rotating objects like propellers or falling stones.

Shake Axes 🧭
Select which axes will be affected by the shake:
Positive (+X, +Y, +Z) and negative (-X, -Y, -Z) axes can be toggled separately.
Tips:
For horizontal objects (tables, cars), use +X and +Z.
For vertical movement (cranes, balloons), use +Y or -Y.

Shake Modes 🎛️
Shake modes provide different types of shaking animation:
Random:
Random shaking for chaotic movements.
Example: Use for explosions or falling objects.
Sinusoidal:
Smooth, rhythmic movements based on a sine wave.
Example: Suitable for oscillating objects like a rocking boat or pendulum.
Variable Amplitude:
The shaking intensity changes dynamically.
Example: Simulate vibrations that diminish over time (e.g., a spring oscillation).

Bake Options 🍞
Bake Animation on New Layer:
If enabled, the shaking animation will be baked onto a new animation layer, preserving the original animation of the object.
Tips:
Always use Bake Option when working with an already animated object to avoid overwriting the original animation.

Number of Frames 🎞️
Start Frame:
The frame where the shake animation starts.
End Frame:
The frame where the shake animation ends.
Tips:
To create cyclical animations, use an even number of frames to ensure smooth transitions.
Manually adjust the frame range for more precise control over when the shake happens.

Shake Button 💥
Press this button to apply the shake animation to the selected objects in the scene.
The shake will be applied based on the settings you have configured (Translation, Rotation, Axes, Shake Mode).

Email 📧
The email padavanr@gmail.com is displayed in the lower-left corner of the interface.
You can highlight and copy this text using Ctrl+C (or Cmd+C on Mac) to contact the developer.

Tips for Using the Script
Setting Up Axes:
Choose only the axes you need for your scene to avoid unwanted movements.
Shake Modes:
Use Random for explosions or chaotic movements.
Sinusoidal is great for smooth, rhythmic animations like waves or oscillations.
Variable Amplitude is ideal for effects that naturally fade over time.
Frame Range:
Set Start Frame and End Frame to control the duration of the shake animation.
Ensure the frame range covers the whole animation.
Baking Animation:
Always enable Bake Option when working with pre-animated objects to preserve their original keyframes.
Debugging:
If something isn’t working, check the selected axes and frame range. Ensure you have an object selected in the scene.

Conclusion
The Rykov's Control Shaker script provides powerful tools for creating shake animations with a high degree of control. It is easy to use yet flexible enough for complex animation needs. 🎉
If you have any questions or need assistance, feel free to contact the developer at the provided email. Happy animating! 🚀

