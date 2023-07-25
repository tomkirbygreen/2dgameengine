# 2dgameengine

## Installing Mac Dependencies

```
brew install sdl2
brew install sdl2_image
brew install sdl2_ttf
brew install mixer
brew install lua
```

To install `brew` visit `https://brew.sh`.

To discover the correct paths you should invoke:

`sdl2-config --cflags`

and:

`sdl2-config --libs`

NOTE:

Rather than using `#include <SDL2/SDL.h>` you can now just use `#include <SDL.h>`.

