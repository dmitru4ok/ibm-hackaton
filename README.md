# ibm-hackaton
* IBM accessibility hackaton
* CHATGPT warning for those with no bad code tolerance policy.
* Simple ping-pong app using three.js using Web Audio API to simulate 3D surrounding sound.


## Run
1. Go to desired folder folder using terminal cd command
2. execute line by line (UNIX)
```
git clone https://github.com/dmitru4ok/ibm-hackaton.git
cd ibm-hackaton
npm i
npm run dev
```
3. Use headphones
4. Go to lo http://localhost:5173/ in your Chrome(preferably) browser

## nonAcc.html
This file contains and identical application, but without any computational Audio. 
Since I didn't manage to setup vite webserver config,
if you want to try it too:
1. Rename **index.html** to **index.saved.html**
2. Rename **nonAcc.html** to **index.html**. This will make file visible to _vite_ webserver as default one.
3. Run 
```
npm run dev
```
This will make **nonAcc.html** an entry point into the app. 
4. Go to http://localhost:5173/