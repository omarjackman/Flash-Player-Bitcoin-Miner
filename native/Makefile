# Copyright (C) 2012 Marek Burza
#
# Flash Player Bitcoin Miner
#
# This builds the mining portion of the native standalone miner (for testing purposes).
# The communication with a mining pool is done by run.py Python script.
#
# This code is free software: you can redistribute it and/or modify it under
# the terms of the GNU Lesser General Public License as published by the Free
# Software Foundation, either version 3 of the License, or (at your option)
# any later version.
#
# This code is distributed in the hope that it will be useful, but WITHOUT ANY
# WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
# FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License for
# more details.
#
# You should have received a copy of the GNU Lesser General Public License
# along with code. If not, see <http://www.gnu.org/licenses/>.
ALL: app

app:
	gcc -O3 miner.c -o miner -DSTANDALONE
