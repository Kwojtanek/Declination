This is custom Declination Field for django orm.

    Declination is geographical counterpart of latitude in cartesian system but projected on a sphere.
    Data is represented in sexagesimals including hour not biger than 90 degree, 1/4 of sphere.
    Declinations with magnitudes greater than 90° do not occur, because the poles are the northernmost and southernmost points
    of the celestial sphere.

     Only representation and savings are changed and data is stored in arc seconds.
     Field inherits from simple integer field.
     Becouse of above it allows user to do all standard aritmetics.

To install copy this repository to your project file and simply import DeclinationField class
