# VirtualCampus Web Server

## How To Install 
Install [NPLRuntime](https://github.com/LiXizhi/NPLRuntime/wiki), then

```
git clone git@github.com:Elshadow/VirtualCampusWeb.git
```

Run `./start.sh` on linux, or `start.bat` on windows, 
or run with following npl command directly.  
```
npl -d root="www/" port="8098" bootstrapper="script/apps/WebServer/WebServer.lua"
```

To test it, open `http://localhost:8098`

Dependencies: 
  - [main package](https://github.com/NPLPackages/main), see git submodules for details

Web server root directory is `www/` 

