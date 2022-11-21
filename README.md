# wine
Wine builds made by me, Oro. Probably using wine-tkg-git

### How to use

For wine-wayland builds, run them with the variables `DISPLAY=''` and `WAYLAND_DISPLAY='wayland-0'` to put them on Wayland. Otherwise, they will run through X/Xwayland. 

On Steam, you can set the launch args like so: 
```export DISPLAY='' && export WAYLAND_DISPLAY='wayland-0' && %command%```
