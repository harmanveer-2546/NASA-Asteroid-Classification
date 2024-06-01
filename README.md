## INTRODUCTION:<br>
What all is out there in space is still a mystery. Scientists keep on trying to search for something new in outer space. While a lot is expected to be discovered, let us look at what has been found.<br>

## ASTEROIDS:<br>
Yes!! An accidental discovery made in 1801 by the Italian priest and astronomer Giuseppe Piazzi, led to what we call an asteroid today. Giuseppe found the first asteroid named Ceres orbiting between Mars and Jupiter. Since then, many asteroids have been discovered and studied by space organizations like NASA.
Asteroids are minor planets, especially of the inner Solar System. Larger asteroids have also been called planetoids. There exist millions of asteroids and the vast majority of known asteroids orbit within the central asteroid belt located between the orbits of Mars and Jupiter, or are co-orbital with Jupiter (the Jupiter Trojans).<br>
The study of asteroids is also crucial as historical events prove some of them to be hazardous. Remember the Chicxulub crater? — The crater formed by an asteroid that probably snuffed out all the dinosaurs, 65 million years ago.<br>

## ASTEROID DATASET:<br>
Searching on Kaggle, I found NASA’s dataset about some of the asteroids discovered so far. The data is about Asteroids and is provided by NEOWS(Near-Earth Object Web Service). The dataset contains various information about the asteroids and labels each asteroid as hazardous or non-hazardous.

Some of the features’ description is given below:<br>

1. ‘Neo Reference ID’: This feature denotes the reference ID assigned to an asteroid.<be>

2. ‘Name’: This feature denotes the name given to an asteroid.<be>

3. ‘Absolute Magnitude’: This feature denotes the absolute magnitude of an asteroid. An asteroid’s absolute magnitude is the visual magnitude an observer would record if the asteroid were placed 1 Astronomical Unit (AU) away, and 1 AU from the Sun and at a zero phase angle.<be>

4. ‘Est Dia in KM(min)’: This feature denotes the estimated diameter of the asteroid in kilometers (KM).<be>

5. ‘Est Dia in M(min)’: This feature denotes the estimated diameter of the asteroid in meters(M).<be>

6. ‘Relative Velocity km per sec’: This feature denotes the relative velocity of the asteroid in kilometres per second.<be>

7. ‘Relative Velocity km per hr’: This feature denotes the relative velocity of the asteroid in kilometer per hour.<be>

8. ‘Orbiting Body’: This feature denotes the planet around which the asteroid is revolving.<be>

9. ‘Jupiter Tisserand Invariant’: This feature denotes the Tisserand’s parameter for the asteroid. Tisserand’s parameter (or Tisserand’s invariant) is a value calculated from several orbital elements(semi-major axis, orbital eccentricity, and inclination) of a relatively small object and a more substantial‘ perturbing body’. It is used to distinguish different kinds of orbits.<br>
10. ‘Eccentricity’: This feature denotes the value of eccentricity of the asteroid’s orbit. Like many other bodies in the solar system, the realms asteroids make are not perfect circles, but ellipses. The axis marked eccentricity is a measure of how far from circular each orbit is: the smaller the eccentricity number, the more circular the realm.<br>
11. ‘Semi Major Axis’: This feature denotes the value of the Semi Major Axis of the asteroid’s orbit. As discussed above, the realm of an asteroid is elliptical rather than circular. Hence, the Semi Major Axis exists.<br>
12. ‘Orbital Period’: This feature denotes the value of the asteroid's orbital period. The orbital period refers to the time taken by the asteroid to make one full revolution around its orbiting body.<br>
13. ‘Perihelion Distance’: This feature denotes the value of the Perihelion distance of the asteroid. For a body orbiting the Sun, the point of least distance is the perihelion.<br>
14. ‘Aphelion Dist’: This feature denotes the value of the Aphelion distance of the asteroid. For a body orbiting the Sun, the point of greatest distance is the aphelion.<br>
15. ‘Hazardous’: This feature denotes whether the asteroid is hazardous.<br>

To sum up, the features present in the dataset cover not only the information about the geometry of the asteroid but also its path and speed.<br>
<br>Being a data science enthusiast, I thought of using machine learning to predict whether an asteroid could be hazardous or not.
