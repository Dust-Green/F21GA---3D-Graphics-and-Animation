First off I'm bad at Git. I've never been very good at getting myself to update repos until I have everything done which defeats the process. 

# Models

For this I created, technically, 8 models but since I consider about 3 of them to be pretty simple I'm considering it as maybe 6 or 7 when all's said and done. 

## Bicycle

I started off making a model based off my most recent hobby/hyperfocus. My Cannondale Topstone gravel bike. 

<img src="Image References\Bike.PNG" alt="Gravel Bike" style="height: 400px; width:1200px;"/>
<img src="Image References\BlendBike.PNG" alt="Bike Model" style="height: 400px; width:1200px;"/>

I'm more or less happy with how this came out. I kept it simple and ignored a lot of the complex modeling. So no gears, drivetrain, brakes, shifters, derailers etc.

The wheels are seperated from the main body  of the bike(and each other) and all are made children to an empty axes. This was so that I could animate the wheels rolling easily if needed. I colored it blue just so that it would stand out a little compared to the plain black/graphite of my real bike. 

## Heroshot Splatoon 3

The other thing that's been taking up a lot of my free time has been Nintendo's 'Splatoon 3' and I've always loved the weapon designs of the game. I especially fell in love with the newest version of the 'Heroshot' the weapon you use throughout most of the story mode. The roll of 3d printer filament and resin printer cartridge that serve as the weapon's 'Ammo' are especially cool to me and it's big blocky overall shapes felt like it would lend itself well to this low poly style of modelling I decided to implement. I'm probably the most happy with how this model came out overall. I also found a youtube video where someone made a prop of the weapon but they had a lot of details that proved invaluable to model it in Blender.

<img src="Image References\Heroshot.PNG" alt="Splatoon 3 Hero Mode Reference" style="height: 400px; width:1200px;"/>
<img src="Image References\BlendShot.PNG" alt="Splatoon Model" style="height: 400px; width:1200px;"/>

## Vending Machine

Trying to come up a with a scene for these two models seemed tricky as they started as my 'learning blender' models and I was just picking the first thing that seemed interesting to me. I had recently started watching the anime 'Yowamushi Pedal' again because of my previously mentioned hyper-fixation with bikes and this road cycling anime seems to have a lot of character scenes happen in front of outside vending machines so that became the backdrop for my scene and my third model. 

<img src="Image References\Vending.PNG" alt="Vending Machine Reference" style="height: 400px; width:1200px;"/>
<img src="Image References\YowaPeda.jpg" alt="Aoyagi from Yowamushi Pedal next to a vending machine" style="height: 400px; width:1200px;"/>
<img src="Image References\VendBlend.PNG.jpg" alt="Vending Machine Model" style="height: px; width:px;"/>

This was surprisingly difficult. I'm not super happy with how the internal part of the vending machine came out. Based off the photo reference apparently machines in Japan use buttons along individual shelves for selection rather then the number/letter keypads that I'm more familar with from the states. The shelves are also not evenly spaced and the glass texture was difficult to get working but it still came out 'workable' overall so I can't complain. 

## Drinks

Following up that I didn't want to leave the vending machine empty and I made a personal rule not to use image textures as a way to skirt around making models for anything. Which might have been a silly restriction but I think it helped me find different solutions to issues I encountered. I decided to go with two drinks that again show up frequently in 'Yowamushi Pedal'. Pocari Sweat, a popular sports drink in Japan. Similar to Gatorade in the US or Lucozade in the UK. Following that up I made a simple can of Pepsi/Bepsi. The show doesn't have the rights to US licensing so they can't use the actual name. I decided to play homage to that by actually shrinkwraping the text 'Bepsi' around the model can. 

<img src="Image References\DrinkBlend.PNG" alt="Drinks Model" style="height: px; width:px;"/>
<img src="Image References\Bepsi.PNG" alt="Arakita with Bepsi" style="height: px; width:px;"/>
<img src="Image References\Pocari.PNG" alt="Pocari Bottle" style="height: px; width:px;"/>

## Bench

Not much to say here but most of these outdoor vending machines in Japan seem to have seating nearby as sort of mini rest stops so I added a colorful bench to also add some more variety to the scene. It also makes blue the sort of main color that is then constrasted by the warmer colors from the hero shot and vending machine all mellowed out by the sun/sky. Plus these sort of light blues are my favorite colors so it becomes my default color choice.

<img src="Image References\BenchBlend.PNG" alt="Bench Model" style="height: px; width:px;"/>

## Trees and the Terrain 

Last but not least the nature/outside bit. I struggled for awhile on how to make the trees. I found a lot of different tutorials and examples online that all tackled the problem in different ways but it took a while for any of the ideas or methods to really connect with my way of thinking. I settled on this pretty creative idea of using single vertices that you then add a 'skin' and 'subdivision surface' modifier to the overall rig. This lets you create the body of the tree. Then using icospheres and the 'random' transform movement creates pretty interesting low poly leaves. I then used the same technique to make some bushes to fill in the hill. The hill is made up using a lot proportional editing to move around vertices and overall I am very pleased with the results. 

<img src="Image References\TreeBlend.PNG" alt="Tree Model" style="height: px; width:px;"/>

<img src="Image References\HillBlend.PNG" alt="Hill and Trees" style="height: px; width:px;"/>

<img src="Image References\TopDownBlend.PNG" alt="Topdown Overall View" style="height: px; width:px;"/>

## Materials/Lighting/Render

Overall for all the materials and colors I used the default 'Shade Flat' and used color palettes from lospec.com an absolutely amazing resources I found for pixel art and other low poly type things. Specifically the endesga and duel palettes.

Lighting was a combination of the 'Dynamic Sky' add-on that blender has as well as a Sun light to create some more pronounced shadows on everything. 

The render is also not too involved most of the settings are defaults with a few refractions turned on for the glass materials and things turned up for quality where my laptop can handle it. 

# Final Image

<img src="FinalScene.PNG" alt="Final Render" style="height: px; width:px;"/>

# Reference/Links

[Endesga Palette on Lospec](https://lospec.com/palette-list/endesga-64)

[Duel Palette on Lospec](https://lospec.com/palette-list/duel)

[Splatoon 3 - Hero shot | Replica prop Youtube](https://www.youtube.com/watch?v=CIk-_3_ERYg)

[Blender Bicycle Tutorial Youtube](https://www.youtube.com/watch?v=6g-iv_QJOjo)

[Blender Glass Material Tutorial Youtube](https://www.youtube.com/watch?v=CtfNtpJa3hU)

[Low Poly Tree Tutorial Youtube](https://youtu.be/V0LyhVM6ILk)