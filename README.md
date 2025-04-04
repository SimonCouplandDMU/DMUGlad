glad
====

Glad for use in DMU C++ modules.

Include in your CMakeLists.txt file using FetchContent.

## Example

```c
FetchContent_Declare(
  glad
  GIT_REPOSITORY https://github.com/SimonCouplandDMU/DMUGlad.git
  GIT_TAG        gl4.6_core_ARB_bindless_texture
 )
 
 FetchContent_MakeAvailable(glad)
```

The use as per the glad docs and examples at https://github.com/Dav1dde/glad

