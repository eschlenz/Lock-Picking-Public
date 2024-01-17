# ASSA Pin Models

ASSA security pins recreated in CAD and exported as STLs. Models included are:

* Gin Drivers
* Barrel Drivers
* Tree Drivers
* Tapered Drivers
* Side Pins
* Torpedo Key Pins

The original CAD designs are publicly available for you here: [OnShape](https://cad.onshape.com/documents/176fe9eabd277f7d3a69e7b4/w/a9a9295e99a16ee94f090353/e/b16dd582293e6b9c6d4326a5?configuration=List_bMwezQiz2Jqhxx%3DDefault%3BList_nkgbB6XMHEotgr%3DB___196____5mm&renderMode=0&uiState=65a351917329370a4f51c2d3)


# Scales
Every model will include at least one 10X scaled version (relative to the real world pins), without any provided supports. For pins where I had
literature on the different (real world) pin sizes, I also provided those. Additionally, I felt that some pins printed better with built-in 
supports because they are easy to remove and leave a nicer finish. Where possible (and logical), I provided different pre-scaled versions of 
these.

If you want an arbitrarily scaled version of a pin your best bet is to pick the basic 10X model (without built in supports), and scale it in
your slicer software. Depending on which pin you choose, you may also need to specify your own supports.

# File Naming Convention
Each file follows a naming convention that looks something like this: `gin_driver_c_25x_bis`. Please note that some files may not include some
parts as seen in the example file name because they did not apply or were not relevant.

File name parts explained:

1. 'gin_driver' - The type of pin.
2. `a`, `b`, `c`, `d` - Corresponds to the real world size some pins come in from factory. If absent, there are no variants of factory sizes supplied.
3. `Nx` - The scaled up multiplier.
4. `bis` - If present in the filename, this stands for "built in supports".

# More On Supports
The only files that will print without supports at all are the Tapered Drivers and the Torpedo Key Pins. All others need some kind of support material, whether
it's the STL files with built in supports, or DIY.

# Step Files
Originally, I included step files, but there are just too many variants to these models. It's hard enough to generate all of these STLs for easy printing.
If you need or want the original step files, they can be exported from the original CAD files. The link to the OnShape CAD designs is above.