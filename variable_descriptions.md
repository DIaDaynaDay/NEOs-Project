Variable Descriptions
======

Final dataset

1. id - Object ID in the database
2. full_name - Full official name of the object
3. pha - Potentially Hazardous Object flag
4. H - Absolute magnitude parameter. An asteroid’s absolute magnitude is the visual magnitude an observer would record if the asteroid were placed 1 Astronomical Unit (au) away, and 1 au from the Sun and at a zero-phase angle.
5. orbit_id - Orbit ID in the database
6. epoch, epoch_mjd, epoch_cal - Orbital characteristics may vary depending on interactions between bodies, so orbital characteristics are usually reported for the specific date they were observed and calculated. The columns represent the same date in different formats, first 2 in astronomical form, and the last one in conventional date/time form.
7. equinox - In astronomy, there are several ways to give an object's location in the sky. The [picture](https://drive.google.com/file/d/1kf1LqB0O_z5PH3kcupEw803se81BW827/view?usp=sharing) shows the main system in use. Equinox is a point on the celestial sphere where the Sun is situated every year on 21 March, during the Spring Equinox, it is the point that mostly stays the same, so it's convenient to use as the origin for the right ascension. But it is not completely immobile, it moves, but very slowly. Besides, there is also a "proper motion" of the stars, as they also move by themselves relative to the Sun, but very slowly as well. These factors cause star charts to be updated every 50 or so years, so when there is a star chart or object's location is given in some way, they also have to specify the epoch of observation, epoch currently used is J2000, so location of stars and equinox point is given as it was on January 2000.
8. e - Orbit's eccentricity, how oval the orbit is, where 0 is perfectly circular
9. a - Semi-major axis length in au. Biggest axis of the ellipse.
10. q - Perihelion distance in au, the closest distance from the object to the Sun
11. i - Inclination - angle in degrees between the object's orbit and the ecliptic plane (plane made by the Earth's orbit)
12. n - Mean motion, how many degrees the object moves around its orbit per day
13. tp, tp_cal - Time of perihelion passage in two different units
14. per, per_y - Sidereal period in days and years respectively, sidereal period is a period of one revolution around a parent body, in this case - the Sun, this is essentially that object's year
15. moid, moid_ld - Earth Minimum Orbit Intersection Distance, how close can this object approach Earth's orbit. In au and Lunar Distances respectively.
16. moid_jup - Jupiter Minimum Orbit Intersection Distance, how close can this object approach Jupiter's orbit in au 
17. t_jup - Jupiter Tisserand Invariant, it's a value calculated from object's and Jupiter's orbital characteristics, used to distinguish different groups of asteroids
18. sigma_e, sigma_a, sigma_q, sigma_i, sigma_n, sigma_tp, sigma_per - Sigma values which are uncertainties of the values given above. For example, sigma_e is uncertainty in eccentricity.
19. class - Orbit class, there are 4 classes of orbit: 1) Amors (AMO) - Earth-approaching NEO with orbits exterior to Earth's but interior to Mars, 2) Apollos (APO) - Earth-crossing NEO with semi-major axes larger than Earth's, 3) Atens (ATE) Earth-crossing NEO with semi-major axes smaller than Earth's 4) Atiras (ATI) NEO whose orbits are contained entirely with the orbit of the Earth. This is a [picture](https://cneos.jpl.nasa.gov/images/neo_orbit_types.jpg) for reference.
20. Times Approached - Number of times each object has a close approach with Earth
21. v average - Average velocity of each approaching object (km/s)

Note
* au - One Astronomical Unit (au) is approximately 150 million kilometres (km)
* LD - One Lunar Distance (LD) is approximately 384,000 kilometres (km)