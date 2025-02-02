# mulle.js

Mulle.js is an attempt to recreate a wonderful game from the past and bring it to modern platforms, and fix some issues along the way.

You need to own the original release of Mulle Meck Bygger Bilar to use Mulle.js.


## Mac
Install dependencies
* `brew install ffmpeg imagemagick nodejs npm optipng`


## Linux
Install dependencies
* **Arch Linux:** `sudo pacman -S python python-pip ffmpeg imagemagick nodejs npm`
* **Debian/Ubuntu:** `sudo apt install python3 python3-pip ffmpeg imagemagick nodejs npm optipng`

Venv
```
python3 -m venv venv
```

```
source venv/bin/activate
```

Python
`sudo pip install -r requirements.txt`

To download
```
python build_scripts/build.py download
```

You can then generate and start the Mulle.js website, and access it at http://localhost:8080/
```
npm install
npm run build
npm start
```

## Windows
Install dependencies  
Download and install Python3 from https://www.python.org/downloads/  
Download and install imagemagick from https://www.imagemagick.org/script/download.php choose ffmpeg as option during installation

`pip3 install PyTexturePacker pydub bitstring`

Mount Mulle Meck Bygger Bilar ISO  
`python3 extract.py <mounted dir>`

You can then generate and start the Mulle.js website, and access it at http://localhost:8080/
```
npm install
npm run build
npm start
```
[![JavaScript Style Guide](https://cdn.rawgit.com/standard/standard/master/badge.svg)](https://github.com/standard/standard)
