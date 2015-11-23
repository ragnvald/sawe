ReadMe created by Andrew Jacobson, July 2015

This file (GE_Grids_2015) is a binary layer of anthropogenic land cover in East Africa. The coordinate system is WGS84 and has 
a resolution of 0.01 degrees. The grid value of 1 represents grid cells where >50% of the land cover is converted to human 
land uses such as roads, towns, croplands, mines etc. 0 represents land cover that is >50% natural. We have 
not added in water in this version (but previously used GLWD3; see Tif (Fig 2) for a graphic of this dataset with water). 

Additional details on methodology can be found in Jacobson et al. (2015). A novel approach to mapping 
land conversion using Google Earth with an application to East Africa. DOI 10.1016/j.envsoft.2015.06.011. 

GE_holes_clip.tif is the pre hole-filled version of the land cover data but otherwise identical to the GE_Grids_2015 layer. 

Both layers are updated from that which is used in the publication. We updated some of the NoData holes based on new imagery
since the time of the analysis. 

We are including both the pre hole-filled layer (Ge_holes_clip) and the final layer (GE_Grids_2015) for completeness. The user can 
choose to fill in the NoData holes in whatever way they prefer. In the manuscript, we used human population density as we were 
comparing different land cover data. However, we achieved higher levels of agreement between Africover, a 30m land cover dataset, 
than the human population density data. Therefore, the final layer here is not the same as that tested in the manuscript but instead 
one that was hole-filled using Africover. We believe this is the most accurate land cover data set we could achieve at this time. 


For additional questions please contact Andrew Jacobson at andrewwkjacobson@gmail.com


----

Link to publication - http://www.sciencedirect.com/science/article/pii/S1364815215001747 
Link to Africover - http://www.glcn.org/activities/africover_en.jsp