# Ideal gas simulation
Ideal gas simulation in a 3D system at temperature T and volume L^3, where L is the length of the walls.

Just execute it and theoretically it will work (as everything). 

The box is supposed to be a cube but you can change it to be the shape you want. By default, the volume remains constant during the animation but you can change it to be dynamic and study, for example, compressions and expansion.

I encourage you to study, as well as volume changes, temperature (energy) changes.

As allways, all comments will be very grateful.

# Notes
There are two important things I should remark:
- In order for collisions to happen on a ''short'' period of time so as to see how the velocities converge to Maxwell-Boltzmann distribution, the radius of the particles must be `~(V/N)^(1/3)`. Otherwise, the momentum exchanged after each iteration will be small.
- Second, the way preassure is calculated is a bit tricky because if `dt` is two big then the particle will pass through the wall without collinding and, as a consequence, without exchanging momenta with the walls.


# License
    Copyright 2017 labay11

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
