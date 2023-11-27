this is a RPD client web page 100% coded in JavaScript using NodeJs
### how to run
- clone the repo

``` git clone https://github.com/Elemento-Modular-Cloud/Elemento-HTML-viewer.git```
- enter into the RDP dir

```cd Elemento-HTML-viewer/RDP/mstsc.js```
- add the submodule to the repo

```git submodule update --init```
- use npm to download the dependencies

```npm install```
- start the client

```npm start``` or ```node serve.js```
- add the parameters for the connection at /mstsc.js/client/js/parameters.js
- open your browser on http://localhost:9250/

### licenses
- mstsc.js GNU General Public License v3.0: https://github.com/citronneur/mstsc.js/blob/master/LICENSE
- node-rdpjs GNU General Public License v3.0: https://github.com/t-system/node-rdpjs/blob/master/LICENSE
