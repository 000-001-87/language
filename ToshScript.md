# ToshScript
ToshScript is an extended version of Tosh and Scratch that has many extra features like text programming, Scratch-compatible libraries and Scratch API interactions, built-in advanced calculations and XY grid coordinates with sprites and backdrops.
## Examples
### Hello World
```
ScratchProject.new(
    {
        ("Scratch Cat", "green flag clicked"):(
                say "Hello World!"
        )
    },
    {
        "Scratch Cat":{
            costumes: {
                "costume1": ScratchLibrary.Graphics.ScratchCat
            },
            x: 0,
            y: 0,
            size: 100,
            direction: 90,
            effects: {
                ghost: 0,
                mosaic: 0,
                pixelate: 0,
                whirl: 0,
                color: 0,
                brightness: 50,
                fisheye: 0
            }
        }
    }
)
```