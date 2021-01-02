 
 How to include graphics.h in CodeBlocks:

STEP - 1:
       Copy graphics.h and winbgim.h files in include folder of your compiler directory.

       Disk C >> Program Files >> CodeBlocks >> MinGW >> include.
  
       PASTE THESE TWO FILES HERE.
  
STEP - 2:
      Copy and paste libbgi.a to the lib folder of compiler directory.
   
      Disk C >> Program Files >> CodeBlocks >> MinGW >> lib.
   
      PASTE libbgi file HERE.
   
STEP - 3:
       Open Code::Blocks AND Go to Settings >> Compiler >> Linker settings.
    
      Click Add button in link libraries part and browse and select libbgi.a file.
    
      In right part (ie. other linker options) paste commands given below and press ok.

      -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32 
    
 STEP - 4:
       Now you are ready to compile any graphic code on code bloack save  the code with .cpp extension and run
       NOTE: use getch()  function to hold the output window.
 
 
 
   
