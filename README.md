# my-FRIDA-scripts


# Description
Some useful FRIDA javascript tools for mobile security analysis (also shared on: <https://codeshare.frida.re/>), these scripts have been tested only on devices (it is not guaranteed that they work on emulators):

#### Android Multiple Certificate Pinning Bypass
Script to bypass multiple certificate pinning checks in Android apps: 
*  [frida_multiple_unpinning.js](<https://gist.github.com/akabe1/5632cbc1cd49f0237cbd0a93bc8e4452>)

#### Android Universal Certificate Pinning Bypasser
Script to bypass certificate pinning check implemented with a recursive TrustManager in Android apps:
* [frida_universal_pinning_bypasser.js](<https://gist.github.com/akabe1/ac6029bf2315c6d95ff2ad00fb7be1fc>)

#### Android Network Security Config Bypasser
Script to bypass network security config pinning check in Android apps (inspired by other similar scripts as `https://research.nccgroup.com/2017/11/03/bypassing-androids-network-security-configuration/` and `https://cmrodriguez.me/blog/nsc-bypass/`):
* [frida_netsecconfig_bypass.js](<https://gist.github.com/akabe1/3da684903d8e57ec3328432358289b65>)


# GNU License
- Copyright (c) 2019

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>
