# LSP-Spyglass

Minecraft data pack support for Sublime's LSP plugin provided through [the Spyglass language server](https://spyglassmc.com).

## Installation

1. Install the following to Sublime:
	- [Package Control](https://packagecontrol.io/installation)
	- [Arcensoth's language-mcfunction](https://github.com/Arcensoth/language-mcfunction#installing-the-sublimetext-package)
	- [LSP](https://packagecontrol.io/packages/LSP)
2. Run the `Package Control: Add Repository` [command](https://packagecontrol.io/docs/usage) and enter `https://github.com/SpyglassMC/LSP-Spyglass` to add the repository as a package.
3. Run the `Package Control: Install Package` and search for `LSP-Spyglass` to install it as you would a normal package.
4. Restart Sublime.

## Configuration

Spyglass uses its own [config file](https://spyglassmc.com/user/config.html) for feature configuration.

There might also be something that can be changed here but I have no idea what they are for:

- From `Preferences > Package Settings > LSP > Servers > LSP-Spyglass`
- From the command palette `Preferences: LSP-Spyglass Settings`

## Credits

This package used [LSP-bash](https://github.com/sublimelsp/LSP-bash) as a template. The [LICENSE for LSP-bash](https://github.com/sublimelsp/LSP-bash/blob/master/LICENSE) is attached below.

> MIT License
> 
> Copyright (c) 2019 SublimeLSP
> 
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:
> 
> The above copyright notice and this permission notice shall be included in all
> copies or substantial portions of the Software.
> 
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
> SOFTWARE.
