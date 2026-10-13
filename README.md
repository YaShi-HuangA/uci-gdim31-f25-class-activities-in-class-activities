# in-class-activities
## Devlogs
### W1
Write your W1 activity Devlog here.
1.When the Camera is moved out of the Cat GameObject in the Hierarchy, it is no longer a child of the Cat. When the game runs, the Camera no longer follows the Cat's movement or rotation. This happens because child GameObjects inherit the Transform changes of their parent. Since the Camera is no longer a child of the Cat, it stays in its own position instead of moving with the Cat.
2.https://yashi-huang.itch.io/2026inclassactivity1


### W2
Create future Devlog sub-headers with the three # symbols, then write your Devlogs below them.
The r, g, and b variables are floats because RGB color values can have decimal values between 0.0 and 1.0.
The _bounces variable is an int because the number of bounces is a whole number and does not need decimals.
The error showed that the line was missing a semicolon (;) at the end of the statement.

### W3
activity 1 :
1. `GetResponse`: The parameters are `int friendshipLevel` and `bool knowsSecret`, and the return type is `string` because it returns the character's dialogue response.
2. `SetLightDimness`: The parameter is `float sanityLevel` (0–100), and the return type is `void` because the method changes the light directly.
3. `DidPlayerHitBeat`: The parameter is `float keyPressTime`, and the return type is `bool` because it indicates whether the player hit the beat accurately.
Activity 2: Components & Classes Metaphor
A class is like a blueprint for a house. The blueprint describes what a house can have and do, but it is not itself a house in the scene. A Component is like one actual house built from that blueprint. Member variables are the house’s traits, such as its color or number of floors. Methods are the actions it can perform, such as opening a door or turning on a light. Multiple houses can be built from the same blueprint, just as multiple Components can be created from one class.
activity3: I think the balls get extremely bright because their color is multiplied by 1.5 every time they collide. The color keeps increasing with each bounce instead of resetting to the original color, which makes the balls look brighter and brighter, especially in the Scene view.



## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 