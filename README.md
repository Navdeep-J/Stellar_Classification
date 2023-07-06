# Stellar_Classification
Classifying cosmic entities based on their distinct characteristics and properties into appropriate classes.


## Dataset
The data consists of 100,000 observations of space taken by the SDSS (Sloan Digital Sky Survey). Every observation is described by 17 feature columns and 1 class column which identifies it to be either a star, galaxy or quasar.


| # | Feature    | Description                                                     |
|---|------------|-----------------------------------------------------------------|
| 1 | obj_ID     | Object Identifier, uniquely identifies the object in the catalog |
| 2 | alpha      | Right Ascension angle (at J2000 epoch)                           |
| 3 | delta      | Declination angle (at J2000 epoch)                               |
| 4 | u          | Ultraviolet filter in the photometric system                    |
| 5 | g          | Green filter in the photometric system                          |
| 6 | r          | Red filter in the photometric system                            |
| 7 | i          | Near Infrared filter in the photometric system                  |
| 8 | z          | Infrared filter in the photometric system                       |
| 9 | run_ID     | Run Number used to identify the specific scan                   |
| 10 | rereun_ID | Rerun Number to specify how the image was processed             |
| 11 | cam_col    | Camera column to identify the scanline within the run           |
| 12 | field_ID   | Field number to identify each field                             |
| 13 | spec_obj_ID | Unique ID used for optical spectroscopic objects                |
| 14 | class      | Object class (galaxy, star, or quasar object)                   |
| 15 | redshift   | Redshift value based on the increase in wavelength              |
| 16 | plate      | Plate ID, identifies each plate in SDSS                         |
| 17 | MJD        | Modified Julian Date, indicates when the SDSS data was taken    |
| 18 | fiber_ID   | Fiber ID that identifies the fiber pointing the light in each observation |
