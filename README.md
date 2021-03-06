## SHIFT version 6.8.4

## Installation

Automatic install script for Debian based systems Ubuntu, Mint, Debian.

Install Shift (Mainnet)
```
git clone https://github.com/ShiftNrg/shift.git && shift/shift_manager.bash install
```
Install Shift (Testnet)
```
git clone -b testnet https://github.com/ShiftNrg/shift.git && shift/shift_manager.bash install
```
Update Shift Manager
```
./shift_manager.bash update_manager
```
Update Shift Client
```
./shift_manager.bash update_client
```
Update Shift GUI (wallet)
```
./shift_manager.bash update_wallet
```
Start Shift
```
./shift_manager.bash start
```
Stop Shift
```
./shift_manager.bash stop
```
Reload Shift (stop and start)
```
./shift_manager.bash reload
```
Shift node status, is it running or not?
```
./shift_manager.bash status
```
Rebuild blockchain from official snapshot
```
./shift_manager.bash rebuild
```

## Authors
- Mariusz Serek <mariusz@serek.net>
- Goldeneye (Shift Team)
- Ralfs (Shift Team)
- Joey <shiftcurrency@gmail.com>
- Boris Povod <boris@crypti.me>
- Pavel Nekrasov <landgraf.paul@gmail.com>
- Sebastian Stupurac <stupurac.sebastian@gmail.com>
- Oliver Beddows <oliver@lightcurve.io>
- Isabella Dell <isabella@lightcurve.io>

## License

Copyright © 2016-2018 Shift  
Copyright © 2016-2017 Lisk Foundation

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the [GNU General Public License](https://github.com/ShiftNrg/shift/tree/master/LICENSE) along with this program.  If not, see <http://www.gnu.org/licenses/>.

***

This program also incorporates work previously released with lisk `0.7.0` (and earlier) versions under the [MIT License](https://opensource.org/licenses/MIT). To comply with the requirements of that license, the following permission notice, applicable to those parts of the code only, is included below:

Copyright © 2016-2018 Shift  
Copyright © 2016-2017 Lisk Foundation  
Copyright © 2015 Crypti

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.