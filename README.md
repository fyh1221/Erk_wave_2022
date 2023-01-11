# Erk_wave_2022

Erk wave propagation simulation from:

Ultrafast and long-range coordination of wound responses is essential for whole-body regeneration

Yuhang Fan, Chew Chai, Pengyang Li, Xinzhi Zou, James E. Ferrell, Jr., Bo Wang

Copyright (C) 2022 Yuhang Fan

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see https://www.gnu.org/licenses/.

The model, adopted from a recent work (Dieterle et al., 2020), simulated diffusive signaling relay to investigate the effects of cell length, density, orientation, and diversity on Erk activity propagation. This model considers a relay in which cells sense the local concentration of a diffusive signaling molecule and participate in the release of the same molecule to activate neighboring cells. Each cell occupies a specified space in a 2D plane and activates when the average concentration of activator within its occupied space exceeds a certain threshold.

The code requires Python (version 3.7.12). The code runs on Ubuntu 18.04.5 LTS (GNU/Linux 5.4.0-124-generic x86_64) Processor Intel(R) Core(TM) i7-6700K CPU @ 4.00GHz

Python Toolboxes required are:

math (version 3.7) pandas (version 1.3.4) numpy (version 1.20.3) seaborn (version 0.11.2) matplotlib (version 3.4.3)
