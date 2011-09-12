Sequencer
=========

#### a web application for sequencing sync tracks to html5 audio or video tags which exports in JSON  ####

**Author:** 

* Corban Brook [@corban](http://twitter.com/corban) 

Using realtime beat detection can only get you so far when doing sound interactive sequencing of events in visualizations.

This application allows you to create named tracks in sync with key events in music or video in order to trigger transitions, effects, cuts, etc.

The included example loads a banks.js file which contains a JSON object bank of sequencer tracks which are keyed to claps, bass drum, snares, and other elements 
of the included sound file.

These are the same sequency tracks that are used in our demo for the Mozilla Web-o-Wonder: http://hacks.mozilla.org/2011/03/nocomply/

  "The only limit is your own imagination."

  COMMANDS
    
    Mouse
      
      LEFT button   Selects/Deselects a track
      
      RIGHT button  Sets play head
      
    Keyboard
      
      SPACE         Play/pause
      
      ENTER         Sets play head to start of selected track
      
      ESC           Deselects track and resets zoom
      
      -             Zoom in
      
      =             Zoom out
      
      .             Save
      
      ,             Load
      
      \             Delete selected track
      
      a-z           Hold and release to create a new track
      
      0-9           with track selected, Creates cue point
                    without, Sets play head to cue point
                    
      ]             Next track
      
      [             Previous track

