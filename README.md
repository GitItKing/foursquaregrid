# foursquaregrid
Four Square Grid html demo.

[Demo](https://gititking.github.io/foursquaregrid/four_square_grid_cells_swap.html)

This was used as a test case for a userscript that had four  
live feeds displayed. The reason for making the sections move is to facilitate a screen  
capture area that is only necessary to capture one section. By moving the sections around  
all sections can be moved into say a lower left corner.  
  
Do not expect any customizations. There will be no support here for beyond four sections.  
Some coding might be peculiar, ie. the main four images use 'png' files whereas the  
'swap row', 'swap column' and 'orientation' images use base64.  
This is because the userscript only uses the base64 images and I didn't want to include  
them with the userscript. The '1-4' png files are not used nor distributed with the  
userscript.  
The use of JQuery is for ease with the userscript.
  
The sections do not move physically in the html code. All movement is down with css grid  
positioning. This is coded that way because using a clone method would make the physically  
moved div's reload the embedded feed and this was undesirable.


