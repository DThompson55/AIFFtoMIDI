# AIFFtoMIDI
A Reaper EEL2 script that takes a GarageBand User Generated Loop AIFF File that has been imported into a Reaper item and extracts the midi component to a new Reaper tradck/item.

Instructions:
- Save this file to yoru local drive.
- Use the Reaper Action ReaScript/Edit Run to load this script.
- Generate a User defined LOOP in GarageBand and export it as an AIFF file.
- Then import the AIFF file as a media item to a track in Reaper. 
- Select the media item before running this script.
- Run the script
- It will generate a new track with a midi item if there was MIDI in the original file.
- Add a drum FX to the new track. SSD5 seems to match the GarageBand midi mapping pretty well.
 
