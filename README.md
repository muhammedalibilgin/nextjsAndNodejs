# nextjsAndNodejs
## Test Nextjs and Nodejs together

NOT: <br>
-server1.js == server2.js , server1.js not work but server2.js is work. just different between, i add `dir: "./client2`` on the server1.js

* I want to run the server1 file in its location. is there no way?

server1.js:<br>
`const app = next({ dev, dir: "./client2" });`<br>
server2.js<br>
`const app = next({ dev });`;<br>

1- `git clone https://github.com/muhammedalibilgin/nextjsAndNodejs.git`<br>
2- `cd nextjsAndNodejs`<br>
3- `cd client2`<br>
4- `npm i`<br>
5- `node server2.js`<br>

and get the [http://localhost:3000/](http://localhost:3000/) on the browser. its worked success. No problem.<br>

but<br>
6- `cd ..`<br>
7- `npm i`<br>
8- `node server1.js`<br>

Here is error:<br>
![error](assets/error.png)



> I want to run the server1 file in its location. is there no way?<br>


