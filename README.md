How to Compile  Smartdns

Requirement
Build Essential
Rust
Clang
nodeJS+NPM

clone reposity 
https://github.com/pymumu/smartdns

enter to directory
create pkg-config dir
mkdir pkg-config

compile with ui
make WITH_UI=1 install -j

if theres any error
makesure to compile plugin smartdns-ui first with entering the directory
cd plugin/smartdns-ui
make

and try again to compile and wait until complete
