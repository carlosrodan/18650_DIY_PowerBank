# 18650_DIY_PowerBank
18650 DIY Parametric PowerBank

This repo includes the main CAD files for my 18650 DIY battery pack project. I have designed a box to hold the 18650 battery pack and needed electronics. It can be 3D printed. For ease of use I include both the original FreeCAD file so you can use it / modify it as well as the stl and 3mf ready to print. 

You can also checkout this project for more details and for 3D printing directly on makerworld:

https://makerworld.com/models/2656721?appSharePlatform=copy

### How to use it
This model is (almost) fully parametric using a spreadsheet (FreeCAD v1.1). Feel free to play around with the spreadsheet to customize it to your liking. 

I also include a macro that should be imported before changing any parameters. Once imported you can input the number of rows and columns of your own battery pack (green header on the spreadsheet) and the box size will adjust accordingly to fit the pack.

I'm aware the sketches is quite sensitive to parameter adjustments that's way I always use absolute constraints to avoid reversion. I would say it's pretty robust but feel free to submit issues if you find anything.  

### Future improvements

* Ideally the number of middle holes for the side lid would adjust to the width of the pack (using a linear pattern for example with a varying number of instances). However FreeCAD doesn't support zero instances to my knowledge and it's a bit tricky to implement. 

===============================

## License

This project uses multiple licenses:

- **Code (Python, macros, scripts):** MIT License  
- **CAD files and 3D models:** CC BY 4.0 (Creative Commons Attribution 4.0)

This means:
- You are free to use, modify, and distribute everything.
- For CAD/models, attribution is required.
- Code can be used with minimal restrictions under MIT.
