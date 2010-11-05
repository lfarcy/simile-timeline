
                                T I M E L I N E


  What is this?
  -------------

  Timeline is a DHTML-based AJAXy timeline developed as part of the SIMILE
  project (see http://www.simile-widgets.org/timeline/).
  
  This version starts from Timeline v2.3.0 and modifies a few things. The
  main modification consists in removing the dependency on jQuery that was
  considered as an overshoot in a context where jQuery alternatives like
  Prototype or DOJO are already used.
  
  Therefore, jQuery is no more bundled and loaded in SIMILE Ajax library. 
  It is no more used either by Timeline. Fortunately, in the original v2.3.0,
  it is only used once to get an animation effect when the timeline is resized.

  The author of this fork wants to thank original Timeline contributors for the
  excellent work they have been doing to make this awesome Javascript widget 
  available to everyone.
  
  Running Timeline
  ----------------

  Timeline consists of static resources, Javascript libraries,
  image files and css files. All you really need is to
  serve those resources off a web server. Any web server will do.

  Two ways to access the library
  
  1. Unzip either timeline_source.zip or timeline_libraries.zip into
     a directory served by a webserver.
     
     timeline_source.zip includes complete source and example files. Use your
     browser to see the examples at
     .../timeline_directory/src/webapp
     
     timeline_libraries.zip is the minimum install of the bundled js libraries,
     css and image files
     
  2. No web server? The timeline project includes a small webserver called
     Jetty (use the timeline_source.zip file)
     a) install the Java runtime from Sun
     b) unzip timeline_source.zip to an install directory
     c) Open a shell or command prompt to the install directory and type:
  
     [win32]> run
     [unix/macosx]> chmod +x run; ./run

     and then point your browser to
  
     http://127.0.0.1:9999/timeline/
  

  How do I customize Timeline?
  ----------------------------

  Refer to the Timeline web site at 
  http://code.google.com/p/simile-widgets/

  
  Mailing List and Forum
  ----------------------
  
  Join the community by joining the Google Group SIMILE Widgets
  http://groups.google.com/group/simile-widgets/


  Licensing and legal issues
  --------------------------

  Timeline is open source software and are licensed under the BSD license
  located in the LICENSE.txt file located in the same directory as this very file
  you are reading.



  Credits
  -------

  This software was created by the SIMILE project and originally written
  by the SIMILE development team (in alphabetical order):

   - David François Huynh <dfhuynh at csail.mit.edu>




                                --- o ---


  Thanks for your interest.




                                                        The SIMILE Project
                                                      http://simile.mit.edu/

