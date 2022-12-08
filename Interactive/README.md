# Interactive Intro

This portion of the project was ROUGH. It took me several days of headache just to get the template to work properly for me. Using both Stefano's and the version provided by our classmate Cam. Neither wanted to work with my computer at home. After finally getting in some time at the Game Studio lab I was able to figure out the issues surronding the template and actually get working. 

# Getting the models loaded in
The basic template does not like taking in multiple models so a work around needed to happen. I had to load up blender again and join together multiple models. I ran into a handful of issues here but I was able to get at the very least the bike and bench loaded up and have the correctly loaded textures. I benefited a lot from my previous work of keeping everything very simple as others had an even worse time.

# Basic Interaction

Running low on time I did my best to add some simple interaction. Using some of the existing code for moving the model around I tweaked it to work with the camera so that you can zoom in and out as well as move the camera to the left and right. 
```c++

if (keyStatus[GLFW_KEY_W]) cameraPosition.z -= 0.10f;
if (keyStatus[GLFW_KEY_S]) cameraPosition.z += 0.10f;
if (keyStatus[GLFW_KEY_A]) cameraPosition.x += 0.10f;
if (keyStatus[GLFW_KEY_D]) cameraPosition.x -= 0.10f;
	
```

# Lights

Using the lab information I was able to add in the basic lights but I wanted to add more interactivity. I tried to use a simple keystatus to turn off and on the lights. This didn't work as intended but after some tweaking I got it working by making use of the `onKeyCallBack` method. 

```c++ 
if (action == GLFW_PRESS && keyStatus[GLFW_KEY_F])
	{
		ia.x = 0.0f;
		ia.y = 0.0f; 
		ia.z = 0.0f; 
		ia.w = 0.0f;  
	} else if (action == GLFW_RELEASE) {
		ia.x = 1.0f;
		ia.y = 1.0f;
		ia.z = 1.0f;
		ia.w = 1.0f;
	}

```


# Framebuffer

I had wanted to add some framebuffer affects but after losing so much time just trying to get the project working I was unfortunately really strapped for time. I had intended to add a greyscale effect and bind it to a key similarly to what I did with the lights. I couldn't quite get it to work but this was the basic lines for the greyscale effect. 

```c++ 
FragColor = texture(screenTexture, TexCoords);
float average = (FragColor.r + FragColor.g + FragColor.b) / 3.0;
FragColor = vec4(average, average, average, 1.0);
```
Take all the color in the scene and just flatten it out by a value, in this case 3. 

# Video 

Include in the folder this readme file is there should be, hopefully, a video that showcases all of these interactions and effects. 