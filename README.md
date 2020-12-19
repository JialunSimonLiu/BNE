# Brazil-nut-effect
![Alt Text](https://github.com/JialunSimonLiu/Brazil-nut-effect/blob/main/Picture.png)
The initial/basic code is programmed as follows to investigate the brazil nut effect:
**1. Initial conditions.** In a two dimensional system, particles are set to have circular shapes and never overlap with each other.
**2. Equilibrium simulation after ‘pouring’** The Monte Carlo method was implemented to demonstrate the process of ‘pouring’, a
process of pouring particles into a container until they are settled by gravity.
**3. Shaking simulation** Particles are constantly lifted and settled throughout the process of shaking. The Monte Carlo method and the largest nearest neighbor distance are used to speed up this process.

**Optimised code:** The updated version modells the box as a grid, and the presence of a particle excludes its position from the grid to represent the fact that this position was occupied. Compared to the old version, the newest one has made sure no particles would overlap with each other without the use of loops and saves 90% of efficiency. How it works is to delete all the integer coordinates of particles from the system, hence eliminate the options for the new particles to select.

