# [WireGuard](https://www.wireguard.com/) for iOS

## Building

- Clone this repo:

```
$ git clone https://git.zx2c4.com/wireguard-ios
$ cd wireguard-ios
```

- Init and update submodule:

```
$ git submodule init
$ git submodule update
```

- Rename and populate developer team ID file:

```
$ cp WireGuard/WireGuard/Config/Developer.xcconfig.template WireGuard/WireGuard/Config/Developer.xcconfig
$ vim WireGuard/WireGuard/Config/Developer.xcconfig
```

- Open project in XCode:

```
$ open ./WireGuard/WireGuard.xcodeproj
```

- Flip switches, press buttons, and make whirling noises until XCode builds it.

## MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
