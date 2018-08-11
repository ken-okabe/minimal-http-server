# minimal-http-server
node minimal-http-server just works as expected, good for built-in something


## Usage

```
import { server } from "./server.js";

const dir = "./www";
const port = 19999;
const serverUp = () => {
    console.log("server up " + port);
};

server(dir)(port)(serverUp);

```


To take advantage of ES6 Module(ESM),

recommend to use

https://www.npmjs.com/package/esm


or simply copy&paste the function to your projcet from the source-code :

https://github.com/kenokabe/minimal-http-server/blob/master/server.js

## MIT License

