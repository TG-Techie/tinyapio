# tinyapio
A small tool to compile and upload verilog projects to boards supported by the apio project

# install
run:
```
pip install apio==0.4.0b5 tinyprog;
apio install system scons icestorm iverilog;
apio drivers --serial-enable;
```

clone this repo into /usr/local

then add:
```
#set path for tinyapio
PATH="$PATH:/usr/local/tinyapio/bin"
export PATH
```

to your .bash_profile or .profile file, often in ~

# use
after instal run tinyapio --help for avaibale commands
