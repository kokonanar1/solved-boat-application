Download Link: https://assignmentchef.com/product/solved-boat-application
<br>
In this project, you will produce a Boat application. Each Boat has the following attributes: name, speed, angle, and power. The Boat names should be read from a text file “boats.txt”. You can assume there will be a maximum of 100 boats in the file. For testing, use the following boat names in the boats.txt file:

<em>Sea Monkey</em>

<em>Backdraft</em>

<em>Cast Away</em>

<em>Nautifish</em>

<em>Destiny</em>

The application should be able to accept commands from the user. The user has to provide the commands in the following format:

<em>&lt;Boat name&gt;, &lt;command&gt;</em>

Example:

Sea Monkey, power on

Sea Monkey, turn left

Sea Monkey, speed up

The acceptable commands are the following (Any other command should be considered invalid):

<strong>Command</strong>

<strong>Description</strong>

<strong>power on</strong>

power up the boat

<strong>power off</strong>

power off the boat

<strong>speed up</strong>

increases the boat speed by the minimum speed increment 2 mph

<strong>slow down</strong>

decreases the boat speed by the minimum speed decrement 2 mph

<strong>turn left</strong>

turns the boat to the left by the minimum left turn degree 5 deg

<strong>turn right</strong>

turns the boat to the right by the minimum right turn degree 5 deg

After each command is entered and executed, the state of the boat should be displayed. For Example:

User Enters&gt;&gt; Sea Monkey, power on

<em>Program output&gt;&gt; Sea Monkey is pointing in the direction of 0 deg.</em>

<em>User Enters&gt;&gt; Sea Monkey, turn right</em>

<em>Program output&gt;&gt; Sea Monkey is in 5 deg angle.</em>

<em>User Enters&gt;&gt; Sea Monkey, speed up</em>

<em>Program output &gt;&gt; Sea Monkey is moving in 5 deg angle at the speed of 2 mph.</em>

<em>User Enters&gt;&gt; Sea Monkey, power off</em>

<em>Program output &gt;&gt; Sea Monkey is powered off.</em>

<em>Error checking:</em>

If the user enters an invalid command, a message should be displayed that the command was invalid.

If the user enters a boat name that does not exist, a message should be displayed that the boat not does not exist.

If the user enters a command that is not in the correct format (boatname, command), a message should be displayed that the command format is invalid.