# stobconv
Bash shell script file to android static elf 32bit binary converter

# Usage
use android terminal (recommended termux)
1-Give root acess
```
su
```
2- Execute setup to for configuration
```
./setup
```
3-if everything went fine u should see stobconv binary and workspace and sdk ,in workspace put ur script files and check if all has #!/system/bin/sh at first line! then execute stobconv --help 
```
./stobconv --help
```
4-read instructions for how to use the binary then
```
./stobconv --build
```
5-if build success u will find out dir created and u can see ur binaries at bin folder as long as source files and object in other folders also if anything wrong please chreck logs in out folder!
