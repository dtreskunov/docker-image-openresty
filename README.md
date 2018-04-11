# openresty-ext

Docker image ([link](https://hub.docker.com/r/dtreskunov/openresty-ext/) to Docker Hub) containing [OpenResty](https://github.com/openresty/lua-nginx-module) with the following Lua libraries:

* [d-led/pugilua](https://github.com/d-led/pugilua): bindings for the [zeux/pugixml](https://github.com/zeux/pugixml) XML library
* [craigbarnes/gumbo](https://github.com/craigbarnes/lua-gumbo): bindings for the [google/gumbo-parser](https://github.com/google/gumbo-parser) HTML library
* [SkyLothar/lua-resty-jwt](https://github.com/SkyLothar/lua-resty-jwt): JSON Web Tokens
* [keplerproject/luacov](https://github.com/keplerproject/luacov): code coverage analyzer
* [spacewander/luacov-console](https://github.com/spacewander/luacov-console): unlike luacov's default reporter, `luacov-console` also counts lua files under workdir which weren't touched by tests

This image allows creating high-performance reverse proxies that are able to parse and modify HTML and XML content.

## Usage

TODO