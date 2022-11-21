# wine
Wine builds made by me, Oro. Probably using wine-tkg-git

### How to use (wine-wayland)

For wine-wayland builds, run them with the variables `DISPLAY=''` and `WAYLAND_DISPLAY='wayland-0'` to put them on Wayland. Otherwise, they will run through X/Xwayland. 

On Steam, you can set the launch args like so: 
```export DISPLAY='' && export WAYLAND_DISPLAY='wayland-0' && %command%```

Note that the wine-wayland builds will NOT work inside of Gamescope, as it only gives applications access to an X socket. Wayland applications being used inside of gamescope will instead make windows on your native Wayland compositor.
