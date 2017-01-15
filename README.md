# electron-python

* Electron
 * Photonkit
 * devtron
 * gulp
* Python
 * Flask
 * Flask-RestAPI



```
git clone https://github.com/blucky/electron-python.git your_project_dir
cd your_project_dir
git remote rm origin
npm install
pip install -r requirements.txt
```


```
npm run start
npm run dev
npm run watch
npm run build
```


```
 Electron(Main Process) /
  ├ Electron(Render Process) /
  │  ├ Photonkit
  │  └ webview tag(connect localhost:5000) /
  │    └ vue.js
  ├ Python Process /
  │  └ Flask (server localhost:5000) /
  │    └ flask-restful API (localhost:5000/api/v1/)
```
