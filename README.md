# Circular Sequencer

*Max 8.5*

This Max for Live Device creates MIDI-notes according to the motion of moving agents on a variable grid. <br/>
Every tile on the grid represents a note which gets triggered when an agent reaches it.<br/>
The tiles are also clickable.<br/>
The agents start moving when the transport is *on*. 


#### The controls are:
##### GRID
**X/Y**: number of tiles on each axis of the grid (maximum of 8 each)<br/>

##### MOTION
**Shape**: choose between five shapes of motion: circle, square, triangle, eight and sine<br/>
**X/Y Off**: offset of the shape on the x and y axis<br/>
**Angle**: angle of the shape<br/>
**Rate**: the rotational speed in bars<br/>

##### AGENTS
**Count**: number of moving agents (maximum of 8)<br/>

##### NOTES
**Pitch Offset**: the pitch of the first tile<br/>
**Velocity**: velocity of the played notes<br/>
**Length**: duration of the played notes<br/>

The interface looks like this:<br/>
![Interface](/picture/CircularSequencer.png)
