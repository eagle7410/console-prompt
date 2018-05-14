# console-prompt
console dialog with user.

## Install

``` bash
npm i console-prompt-eagle --save
```
## Example use.

``` node
const ConsolePrompt = require('console-prompt-eagle');
const prompt = new ConsolePrompt();

void async function () {
	let name = await prompt.ask('Enter you name');

	console.log(`You enter name ${name}`);

	process.exit();
}();
```

Result exec this code.

![Result exec this code](https://raw.githubusercontent.com/eagle7410/console-prompt/master/example-result.jpg)

## Authors and developers.

Author and developer [Igor Stcherbina](https://github.com/eagle7410)

## License

MIT License

Copyright (c) 2018 [Igor Stcherbina](https://github.com/eagle7410)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
