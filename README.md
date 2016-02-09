# 628_p1_Share
David's_Group_Work

This is repository for course 628 project one Group [2].

Datasets and R codes are provide here.

##PM 2.5
The U.S. Department of State Data Use Statement at http://www.stateair.net/web/historical/1/4.html applies to these and all data available from the Mission China air quality monitoring program.

##Temperature

Here is the meteorological data where I got the NOAA files updated for the whole of 2015.
http://rda.ucar.edu/datasets/ds091.0/

Note the disclaimer on the bottom (for citation purposes): 

"The Research Data Archive is managed by the Data Support Section of the Computational and Information Systems Laboratory at the National Center for Atmospheric Research in Boulder, Colorado. NCAR is sponsored by the National Science Foundation."

Here's a tutorial for reading netCDF files in R--it looks like there are good R packages specifically designed for reading files in this format, and I will be drawing data for each of the 5 cities in this format.
http://disc.sci.gsfc.nasa.gov/recipes/?q=recipes/How-to-Read-Data-in-netCDF-Format-with-R


#Group discussion plan for week 4 Monday 2/8 

Plan:Each group member explore the data individually at weekends 
(interesting patterns whole datasets or subsets; average issues; hour selecting,etc.)
 
Ideas and results will be shared in group discussion on Monday 1:30 pm -3:30 pm
Datasets and sample codes are availiable in this repo.
Good luck badgers!
                                       

Room Info of Wendt Library

Reservation Id: 158281
Organization: UW-Madison

Date	Start	End	Library / Building	Room	Status
2016/2/8	13:30	15:30	WENDT	Wendt 139C Study Room	Reserved

  By xingxing Feb. 05 /2016

#Group discussion summary for Feb. 8 Monday

Part 1: Presentation for Thursday

Our presentation will have 3 parts  

Use R Presentation 

(Alex: "Rpres" is very similar to R markdown you can insert R codes through each chunk let me know if it doesn't work)

Dataset: 
1)PM 2.5

The U.S. Department of State Data Use Statement at http://www.stateair.net/web/historical/1/4.html applies to these and all data available from the Mission China air quality monitoring program.

2)Meteorological Data (7 variables) 

!!!Shengqian: Fill this part 

(Alex: One or Two pages should be enough for the part of background and data source )


- Part A the intuitive idea based on scattered plots  (David) Time 2-3 mins  

1) Why we choose this 4 specific hours (0 8 12 18)   

2) Raw data plot, How do we deal with missing values(delete 1483 missing values [-999] ) picture name: txx_p1.png , txx_p2.png
It is really hard for us to find any pattern based on the plots above. So we decided to focus on a short short period of time.
        
3) First 50 days and first 100 days  picture name: txx_p3.png , txx_p4.png 

Results: We do not find any very apparent pattern for these five cities given different hours. So we decided to focus on   the average PM 2.5 of each day. 

 - Part B 7 Meteorological variables to explain PM 2.5  (Jiang and Shen together) Time 3-5 mins
 
 Points: Outliers and Regression Model 

- Part C hierarchical model(nest model) to explore the day effects and hour effects on PM2.5  (Alex) Time 2-3 mins 

R.K. Alex before you start your part, indicates that  picture txx_p5.png (Days 51-100 PM 2.5) has a slight pattern that Beijing is higher than the rest of 4 cities.

Part 2: Deadlines and Details

- Each part create a new file at our Github repo. with NAME: PartA, PartB, PartC 

- upload an Rmd file for Thursday's presentation . If any datasets or images need to be loaded, please add a help.txt files to explain it to Alex. (Example: Look help.txt file in PartA)


I will uploaded my part tonight. For Part 2, the deadline is Tuesday Night. Alex will combine three parts together via an Rpres file and the deadline for this part is Wednesday night. I do recommend that we should have another group discussion on Thursday morning. How about 11:15 at STAT department ? Let me know if it works for you guys.  

Good luck

Xingxing Feb. 8
