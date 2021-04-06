# InukshukCompass

Swift Package to add an animated compass view to an iOS app.

## Overview

The Inukshuk compass is an animated view that simulates a magnetic compass.  The view accomdates two parameters to set the angle of rotation and a duration for the animation.

## Installing the Compass

The compass is available as a Swift package.  To install in Xcode, select File->Swift Packages->Add Package Dependency.

## Class Reference

### Class OdometerView

**Public Member Functions**

    public init(frame: CGRect)
     
**Parameters**
     
frame: View frame for the odometer
     
      public func rotateNeedle(duration: TimeInterval, radians: CGFloat)
     
**Parameters**
     
duration:  The duration of the animation for the needle to settle at set direction

radians:  Angle for the needle



