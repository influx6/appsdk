# appsdk
An experimental idea on buildkit for mobile apps

## Sample apps

why ?

- You need stuff for your CI pipelne to work against so you knwo it works.

Which ones:

- flutter
- flutter plugin using golang
- gopherjs app using webview


## Mage 

https://github.com/magefile/mage

why ?

- You need your build CLI to be cross platform 100%
- you can write steps as golang packages that you can import. Its nice.
- Many out there that others are using: https://github.com/search?l=Go&q=magefile%2Fmage&type=Code


mage-dep-os-pkg

- you need your OSX and window setup in a repeatable indempotent way.
- This then is make part of a Mage package

