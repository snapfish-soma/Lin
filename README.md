# Lin

[Lin](https://github.com/questbeat/Lin) is a Xcode plugin that provides auto-completion for `NSLocalizedString`. Both Objective-C and Swift are supported.

This fork adds support to Xcode 7.1 and ``SFLocalizedString`` calls.

![](https://cloud.githubusercontent.com/assets/4681556/10871435/a96f311c-809b-11e5-9d80-e87f694ea42e.png)

## Installation

Download the project and run it, and then relaunch Xcode.  

Lin will be installed in `~/Library/Application Support/Developer/Shared/Xcode/Plug-ins` automatically.

If you want to uninstall Lin, remove Lin.xcplugin in the `Plug-ins` directory.

## Notes

* Xcode 7.1 or later is supported
* Supported functions
  * SFLocalizedString
  * NSLocalizedString
  * NSLocalizedStringFromTable
  * NSLocalizedStringFromTableInBundle
  * NSLocalizedStringWithDefaultValue

## License

Lin is released under the **MIT License**.

Copyright (c) 2014 Katsuma Tanaka

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
