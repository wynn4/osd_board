# osd_board
This is a custom PCB for interfacing between the Micro MinimOSD and the RCE Tricopter V4.  The board is specifically sized to mount on the back side of the V4 fpv transmitter post.  Components for the board can be found by looking at the attached documents.  The voltage regulator should be a SMD packaged LM2940-5 (LDO 5V regulator) and it needs a 0.47uF 0805 package capacitor on the input and a 33uF 0805 capacitor on the output. For more info, see the LM2940 datasheet.  This is the same regulator and capacitor set that was sold for the tricopter power distribution board from RCExplorer.se.  Note: The 5V regulator portion of this circuit is only needed if you are using the 6V or 8V servo power option on the F3FC frame.  The Micro MinimOSD has no voltage regulation so anything above 5V will toast it.

To fabricate your own PCB simply upload the .brd file to oshpark.com

For complete components list, follow this link: http://www.digikey.com/short/30n53w
