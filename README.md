# Automobile-Price-Predictor

### Alogrithms Used:
1. Linear 
2. Multiple
3. Polynomial
4. SVR
5. Decision Tree  
6. Random Forest

### Information about the dataset ####

1. Title: Auto Imports Database

2. Source Information:

   -- Sources:
     1) 1985 Model Import Car and Truck Specifications, 1985 Ward's
        Automotive Yearbook.
     2) Personal Auto Manuals, Insurance Services Office, 160 Water
        Street, New York, NY 10038 
     3) Insurance Collision Report, Insurance Institute for Highway
        Safety, Watergate 600, Washington, DC 20037


3. Relevant Information:
   -- Description
      This data set consists of three types of entities: (a) the
      specification of an auto in terms of various characteristics, (b)
      its assigned insurance risk rating, (c) its normalized losses in use
      as compared to other cars.  The second rating corresponds to the
      degree to which the auto is more risky than its price indicates.
      Cars are initially assigned a risk factor symbol associated with its
      price.   Then, if it is more risky (or less), this symbol is
      adjusted by moving it up (or down) the scale.  Actuarians call this
      process "symboling".  A value of +3 indicates that the auto is
      risky, -3 that it is probably pretty safe.

      The third factor is the relative average loss payment per insured
      vehicle year.  This value is normalized for all autos within a
      particular size classification (two-door small, station wagons,
      sports/speciality, etc...), and represents the average loss per car
      per year.

   -- Note: Several of the attributes in the database could be used as a
            "class" attribute.

4. Number of Instances: 203

5. Number of Attributes: 21 total

6. Attribute Information:     
     Attribute:                Attribute Range:
     ------------------        -----------------------------------------------
     
  1. normalized-losses:        continuous from 65 to 256.
  2. make:                     alfa-romero, audi, bmw, chevrolet, dodge, honda,
                               isuzu, jaguar, mazda, mercedes-benz, mercury,
                               mitsubishi, nissan, peugot, plymouth, porsche,
                               renault, saab, subaru, toyota, volkswagen, volvo
  3. fuel-type:                diesel, gas.
  4. aspiration:               std, turbo.
  5. num-of-doors:             four, two.
  6. body-style:               hardtop, wagon, sedan, hatchback, convertible.
  7. engine-location:          front, rear
  8. wheel-base:               continuous from 86.6 120.9.
  9. length:                   continuous from 141.1 to 208.1.
 10. width:                    continuous from 60.3 to 72.3.
 11. height:                   continuous from 47.8 to 59.8.
 12. curb-weight:              continuous from 1488 to 4066.
 13. num-of-cylinders:         eight, five, four, six, three, twelve, two.
 14. engine-size:              continuous from 61 to 326.
 15. fuel-system:              1bbl, 2bbl, 4bbl, idi, mfi, mpfi, spdi, spfi.
 16. compression-ratio:        continuous from 7 to 23.
 17. horsepower:               continuous from 48 to 288.
 18. peak-rpm:                 continuous from 4150 to 6600.
 19. city-mpg:                 continuous from 13 to 49.
 20. highway-mpg:              continuous from 16 to 54.
 21. price:                    continuous from 5118 to 45400.

8. Contains missing Attribute Values
 
