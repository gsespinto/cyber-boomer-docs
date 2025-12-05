The enemies in **Cyber/Boomer** will be pixelated 2D billboards. They are always aware of the player's position and attack in sync with the beat.
They are spawned in phased out waves, meaning that when a wave starts it progressively spawns the enemies of the wave, instead of spawning all at once.

The basic enemies will be renders of 3D models to save resources, while the bosses will be 3D models in game which are in rendered on to their Sprite 3D. This allows us to have more control hover the bosses attacks and animations.

The enemy's have 3 movement types: **walk**, **fly** and **stationary**.

The basic enemies have 3 states: **idle**, **chase** and **attack**. Their idle while near the player awaiting the music beat in which they enter the attack state and are chasing whenever the player is further away then their attack range. 

The basic enemy's attacks can either be **melee** (just checking if the player is within the attack range) or **shooting** (they fire a projectile towards the player).

The bosses have more complex states and different attacks.

### Basic:
[[Robot Dog]]
[[Robot Dog - Shooter Variant]]
[[Small Flying Drone]]
[[Missile Drone]]

### Bosses:
