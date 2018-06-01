# Ideal Points

This project is a collaboration of Garret Binding (IPZ, University of Zürich), Lucas Leemann (IPZ, University of Zürich), Hannes Weber (Tamedia), and Barnaby Skinner (Tamedia).

The detailed report can be found here: [Link to report (in German)](ADD LINK).

### Objective

The goal of this project was to estimate the ideological position of the various fractions in the lower house in Switzerland. Models were estimated seprately for various issue areas allowing to see whether the political landscape varies by domain.

### Implementation
 
 To estimate the ideological positions we use uni-dimensional IRT models (described in more detail in the text). We relied on *R* and *Stan* to estimate these models.

### Data
The two files with the roll call data were generated by Hannes Weber. They are compressed and need to be un-zipped before running the code (see here: [link to data](https://github.com/lleemann/ideal_gb_ll/tree/master/Data)).

### License
The course content is released under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/) license.
