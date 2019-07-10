## Racetrack content

The files in this directory need to be copied (or moved) to their respective directories.
Assuming that `racetrack_content` is your current working directory run the following commands.

The middle-road trajectories:
```
    cp racetrack0[1,2,3,4].txt ../PythonClient/racetrack/
```

The maps:
```
    cp Racetrack0[1,2,3,4].umap ../Unreal/CarlaUE4/Content/Maps/
```

The elements needed for creating a road element:
```
    cp -r Props ../Unreal/CarlaUE4/Content/
```

The road element definition:
```
    cp -r MyRoad ../Unreal/CarlaUE4/Content/
```

And the `TrackGenerator` (I'm not sure if it's needed, but I'm adding it for completness):
```
   cp TrackGenerator.uasset ../Unreal/CarlaUE4/Content/Blueprints 
```

That's pretty much it, I hope I didn't forget anything.
