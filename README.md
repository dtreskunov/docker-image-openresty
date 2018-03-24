# openresty-ext

Docker image ([link](https://hub.docker.com/r/dtreskunov/openresty-ext/) to Docker Hub) containing [OpenResty](https://github.com/openresty/lua-nginx-module) with:

* [d-led/pugilua](https://github.com/d-led/pugilua): Lua bindings
for the [zeux/pugixml](https://github.com/zeux/pugixml) XML library
* [craigbarnes/gumbo](https://github.com/craigbarnes/lua-gumbo):
Lua bindings for the
[google/gumbo-parser](https://github.com/google/gumbo-parser) HTML
library
* [SkyLothar/lua-resty-jwt](https://github.com/SkyLothar/lua-resty-jwt): Lua JWT library (JSON Web Tokens)

This image allows creating high-performance reverse proxies that
are able to parse and modify HTML and XML content.

## Usage

TODO