## Bruker PV6 guide   
*Courtesy BIL@UAnterp*  
<br>

### Positions
1. Location of the shim voxel. Preferably, the shim voxel should eb ~10% smaller, and the voxel boundaries should cross brain boundaries.    
Shimming can be performed using the anatomical scan, or a single repetition GE-EPI volume.
A B0 map should be acquired before performing the shimming. 
![SHIM package](assets/bruker/shim_position_PV6_7T.png)<br>   

2. Slice pacakges. The first slice should just be at the end of the olfactory bulb. The last slice should be at the start of the cerebelum.     
![Slice package](assets/bruker/slice_position_PV6_7T.png)<br>

3. The FOV saturation band (15 mm, not 4 mm as displayed below), should be located on the inferior boundaries of the slices. 
![FOV package](assets/bruker/FOV_sat_position_PV6_7T.png)<br>

### Parameter cards

4. Exemple parameter cards from PV6.   
TR, TE, n slice, FOV, read-out direction, matrix size    
![1_card](assets/bruker/1_scan_card_PV6_7T.png)<br>    
TR, TE, FA, FOV sat, Fat sat, dummies. **Note the FA is set incorrectly.**    
![2_card](assets/bruker/2_scan_card_PV6_7T.png)<br>
FOV sat. **Note the FOV sat band is set incorrectly.** 
![3_card](assets/bruker/3_scan_card_PV6_7T.png)<br>
FOV, matrix size.   
![4_card](assets/bruker/4_scan_card_PV6_7T.png)<br>  
FOV, matrix size, slice gap, slice order, read-out direction.   
![5_card](assets/bruker/5_scan_card_PV6_7T.png)<br>   
Bandwidth. **Note the bandwidth is set incorrectly.**   
![6_card](assets/bruker/6_scan_card_PV6_7T.png)<br>   
Pulse detail. **Note, can change from system to system**   
![7_card](assets/bruker/7_scan_card_PV6_7T.png)<br>   
Power detail. **Note, can change from system to system**  
![8_card](assets/bruker/8_scan_card_PV6_7T.png)<br>
Shim detail.  
![9_card](assets/bruker/9_scan_card_PV6_7T.png)<br>    

### Image outputs

5. Left anatomical, right functional.   
![1_outcome](assets/bruker/1_anat_EPI_PV6_7T.png)
![2_outcome](assets/bruker/2_anat_EPI_PV6_7T.png)
![3_outcome](assets/bruker/3_anat_EPI_PV6_7T.png)
![4_outcome](assets/bruker/4_anat_EPI_PV6_7T.png)
![5_outcome](assets/bruker/5_anat_EPI_PV6_7T.png)
![6_outcome](assets/bruker/6_anat_EPI_PV6_7T.png)
![7_outcome](assets/bruker/7_anat_EPI_PV6_7T.png)
