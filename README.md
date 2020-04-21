# np issue - aborting np returns 0 status code

1. Run `npm run release`
2. Prompt choose version appears
3. Ctrl+C
4. Howdy

![issue demo](issue_demo.gif)

* npm `release` script executes `np`
* npm `postrelease` hook should be invoked when `release` exits with status 0

This happens only on my Mac (macOS Mojave 10.14.6) with node v11.15.0

Tested also on Windows 10 Home 64 with node v11.15.0 and issue was not reproduced