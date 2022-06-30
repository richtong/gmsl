# GNU Make Standard Library

This just copies over the Sourceforge contents

The manual process is to go to
[Sourceforge](https://sourceforge.net/projects/gmsl/)
then download the latest and copy this over here.

I could automate it by scraping that page, but it does not seem worth it as the
last update was in 2020.

## The Instructions for use

Note this is just concatenate from the v1.19 build

1. Visit [GMSL](http://gmsl.sf.net) for more details

2. To use the GMSL in your Makefile make sure that you have the files

   gmsl
   __gmsl

   Add 

   include gmsl

   to your Makefile(s).

3. To run the GMSL test suite have 

   gmsl
   __gmsl
   gmsl-tests

   And then run

   make test
