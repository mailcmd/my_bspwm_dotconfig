- Follow this tutorial https://www.youtube.com/watch?v=tFEPLwWJwfI
- Copy .config to your home

Compile patched dmenu 
- apk add g++ gcc make x11-dev xinerama-dev xft-dev
- cd ./src/dmenu-XX and make clean; make ; make install

Compile sakura
- apk add glib-dev 
- apk add gtk+3.0-dev
- apk add vte3-dev
- cmake -DCMAKE_INSTALL_PREFIX=/usr .
- make 
- make install



