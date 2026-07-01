Tappy!-June-25-26 is the first version of Tappy! where it only has the grass and dirt that will be at the bottom of the screen in the Home Screen/Main Menu and the main game itself

Tappy!-June-29-26 is the second version of Tappy! it adds the Tappy! scene, which has an animation made from a sprite sheet. It also adds the flying functionality, the main mechanic of the game, it also adds collision, and gravity. The added collision makes it so that you cannot escape the level/screen

Tappy!-June-30-26 adds an animation everytime you "fly." The animation changes the scale and rotation of the AnimationSprite2D, so every time you press the "fly" button, Tappy grows a little bit then shrinks back down, and at the same time wiggles a little bit

Tappy!-July-1-26 adds the Pipe, Laser, and Pipes scenes, Pipes being a combination of the former scenes. It also adds queue_free() to the Pipes scene, along with a node, so that when a Pipes instance is off screen, the memory is cleared of that instance as it is no longer needed. The Pipes scene also adds a Collision2D node that will be used for point scoring and detection if Tappy succesfully crosses through a pipe, that is *that* Collision2D node's only purpose. It also adds other Collision nodes for setting up if you hit a pipe the game is over, but we are not there yet
