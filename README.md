# Chrome-App-pracitce

# Document
- https://developer.chrome.com/apps/first_app

# How to Run (Mac)
- 1. Run it via terminal:
    - Upload src to the chrome://extensions
    - `/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome  --app-id=<id>`
- 2. Run it via nwjs
    - `cd src`
    - `zip -r ../${PWD##*/}.nw *`
    - move the src.nw under <nwjs-osx-sdk> and rename it as 'package.nw'
    - `<nwjs-osx-sdk>/nwjs.app/Contents/MacOS/nwjs .`
    - e.g., `nwjs-sdk-v0.38.3-osx-x64/nwjs.app/Contents/MacOS/nwjs .`
