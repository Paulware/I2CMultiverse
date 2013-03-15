I2C Multiverse

Purpose
  The purpose of the I2C Multiverse is to create lego-like components that 
can easily be added or removed from a project.  Each component will communicate
with the master using I2C (pronounced I-Squared-C).  
  
Form
  Each component will be follow the form of an Arduino shield, but the 
only pins that are passed to each shield are 5V, GND, SDA (A4) and SCL (A5).
Within each component are 2 atmega328s:
  1) communicate with the rest of the system using I2C
  2) communicate with the component which can also be a shield
  
Components
  1) Ultrasonic distance measuring device using US-020 (7 meter range)
  2) HBridge control to drive 2 L298s

Schematics
  1) Dual Atmega 328s which are the heart of each component

Sketches
  TBD

Images
  TBD  
  
Questions/Comments
  paulware@hotmail.com
  
Help with projects
  [I help on Fiverr](http://fiverr.com/paulware/help-with-your-arduino-project)

<a href="https://tindie.com/shops/Paulware/?ref=offsite_badges&utm_source=sellers_Paulware&utm_medium=badges&utm_campaign=badge_large"><img src="https://s3.amazonaws.com/tindie-static/badges/tindie-large.png" alt="I sell on Tindie"></a>
  