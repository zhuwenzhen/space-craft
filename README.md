# space-craft
WSS 20 Space Craft Project

## Project Goal:
Find *where* deep space probes are located at the present time. Create a ‘mission control’ map for the solar system that visualizes the current location and trajectories of a satellite(s) in space. Explore the SPICE framework and connect it to the Wolfram language. 

*SPICE* _https://naif.jpl.nasa.gov/naif/spiceconcept.html_ (https://naif.jpl.nasa.gov/naif/spiceconcept.html)
A NASA JPL data repository that contains information on planetary bodies and man made spacecraft: their trajectories, orientation, location, speed, local properties, etc.

## Project Milestones:

1. Connect SPICE api to The Wolfram Language
2. Extract datapoints from a deep space probe
3. Visualize datapoints in a meaningful way
    1. 2D visualization of a probe (trajectory in space and orientation)
    2. 3D visualization
        

## Project Deliverables:

1. Pull data from SPICE into the Wolfram language in a very easy way.
    1. Addition to Wolfram Data Repository?
2. A function *Plot[] *that takes a spacecraft entity as input and outputs a plotted interactive map of where the spacecraft is.

## Materials

Studying SPICE: https://naif.jpl.nasa.gov/pub/naif/self_training/packaged_docs/
-Self training tutorial

## Notes

*SPICE Architecture*
To get data you must interface with a ‘cell’
A cell contains 2 parts: the data array and a data descriptor (known as a SpiceCell)

