ColorfulBundle
==============

This Symfony2 Bundle provides some Basic functions to work with colors.

It also brings a nice Admin Interface for managing colors. 
ATM this is only a Idea, not a working bundle. 

Ideas:
======

- Have a nice JquerySelector FormType for choosing colors, like DateSelector does for date values. 
- Have a Model for persisting values to Database (look at FOSUB implementation to be ODM aware)
- SonataAdmin class for use in Backends. 



Basic model: 

Color: 
  id: 
  hex: 
  ral:
  cymk: 
  
  
  ->getHexValue()
  ->getRalValue()
  ->getRalString()
  ->getCmykArray()
  ->getRgbArray()
  
  