# GorillaLocomotion

This repository includes some minor improvements to the locomotion system used in Gorilla Tag developed by Lemming.

The scripts have also been added to a Unity package to make installation a lot easier.

## Installation

Add the following url to the Package Manager window in Unity:  
`https://github.com/NtsFranz/GorillaLocomotion`  
![Package Manager UI](package_manager_git.png)

Add the `GorillaLocomotion>Player.cs` script to your player object, and assign the references to the head and hands.
Colliders and rigidbodies must be set up correctly. For an example on appropriate setup, check out the sample scene. You
can set up a unique layer for all the ground objects that are climbable, but you *cannot* have the head/hand colliders
on a layer that is marked as climbable.

### Sample Scene

Import the sample scene by navigating to the package in the Package Manager, then clicking Import in the Samples
section.

The sample scene uses the XR Plugin Management package.

## License

This project is licensed under the terms of the MIT license.
