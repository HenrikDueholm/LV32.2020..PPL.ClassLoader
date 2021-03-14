# LV32.2020..PPL.ClassLoader
Easy support for dynamic loading of classes stored in PPLs.


## Functionality
```
- Scan PPL folder for all classes. 
  The PPL folder is the folder where the PPL built from this project resides, 
  all PPLs are assumed to be placed in the same folder.
- Load any class from the PPL folder by name or qualified name
- Front-loading of cached data or caching (and un-load on request)
- Get filtered class hierarchies 
  (e.g. return hierarchy for all members of the Message class hierarchy)
- Get Members of a class, get hierarchy of a class, get if a class is an interface.
- Populate Tree, Ring and Listboxes with a class hierarchy.
```

## Installation
Link or copy the contained PPL into the folder that contains your other PPLs.
Ideally this would be a PPL folder next to the other source repositories.


## Build and Test
Only contains build products so there are no tests here. 
The tests can be found in the source repository: [LV32.2020..ClassLoader][1]


[1]: https://github.com/HenrikDueholm/LV32.2020..ClassLoader