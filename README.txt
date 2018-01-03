                        Equsol
			======

What is Equsol?
-------------------

Equsol is a shell script for solving equations in the command line. The
equations are stored in a plain text file and can be easily added / modified /
removed depending on the user's preferences.

Equsol is written in bash script.

Downloading
-----------

Latest release of Equsol can be downloaded from http://code.agnibho.com/equsol/

Installation
------------

1. Download the script and place it in your path. Alternatively you can place it
anywhere and create an alias instead.

2. Download the data folder which also contains some working examples of
equation files.

3. Edit the main script and update the DIR variable to contain the path to your
downloaded data folder.

Usage
-----

Equsol can be used from bash command line.

Run equsol without any arguments to see a list of available equations.

You can run equsol with the name of an equation file as argument to solve it.

If the file contains multiple equations you will receive the option to choose
which equation to solve.

After selecting the equation equsol will run the equation and ask for your input
for different variables required in the equation. After entering the values
equsol will run the calculations and print the result in the screen.

The equation files are placed in the data folder. The files can contain one
equation per line. Empty lines are ignored.

While writing equations variables are written within square brackets. Some
examples are available within the downloaded data folder. The lines starting
with # are treated as comments.

Licensing
---------

Copyright (c) 2017 Agnibho Mondal
All rights reserved

This file is part of Equsol.

Equsol is free software: you can redistribute it and/or modify it under the
terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

Equsol is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
Equsol.  If not, see <http://www.gnu.org/licenses/>.

Contacts
--------

Agnibho Mondal
contact@agnibho.com
www.agnibho.com
