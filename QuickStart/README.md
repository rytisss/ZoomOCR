## Quick start

This software has 2 sport modes: basketball and hockey/handball. Each of them have sport-specific features and regions. Also, it is possible to cut only the part of frame, if it is too big or transform the frame if camera is positioned not straight to the lightboard.
  
### Digits recognition and association
To recognize specific region add the controler region and select its value. Execute the following steps:

<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/quick_setup_small.gif" width="1000"/></kbd>  
  
Multiple regions can be adjusted by pressing '**CTRL**' + **Mouse left button** while mouse is dragged. The frame of window which is controlled will be indicated:  
  
<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/all_control_element_shift_small.gif" width="1000"/></kbd>   

### Saving and loading OCR region configuration
Configured OCR regions can be save and loaded on demand. Note that only specific sport configuration can be loaded to that specific sport. That sport needs to be active when loading configuration!

<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/save_load_config.gif" width="1000"/></kbd>  

### ROI adjustment 
If frame is big and the region of interested is quite small, only the small region can be taken into consideration which can reduce CPU load:  

<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/roi_adjustment_small.gif" width="1000"/></kbd>  

### Stabilization regions adjustment 
If there is a lot of movement in the frame (people or other moving object) consider reducing the stabilization region size to be situated more around stabilized object. It might improve stabilizer performance:  

<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/stabilization_region_reduction_small.gif" width="1000"/></kbd>  

### Region transformation 
If the context is not straight, it is possible to transform ('straighten') the context:  

<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/transformation_region_small.gif" width="1000"/></kbd>  

### Region reset 
There is also a way of quick reset of all mentioned region controllers:

<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/regions_reset_small.gif" width="1000"/></kbd>  
