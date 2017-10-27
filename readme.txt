Gramener-Product Team Hiring Exercise_BMSIT
Use​ case​ ​2 - ​2011​ ​ India​-Census

    Indian government carries out census every decade. This dataset contains information from the
    2011 census with district level granularity on population, gender, literacy, socioeconomic status (electricity,​ ​ mobiles,​ Internet)​ ​  
    among​ ​ a lot​ of​ ​ other​ ​ dimensions.

Questions​ ​ to​ ​ answer:


###
    For solving This Problems i used python and its libraries Pandas,numpy,matplotlib,Jupyter-Notebook
####

1. Create​ ​a geographic​ map​ ​of​ ​states​ ​with​ ​low​ ​literacy​ ​rates.
    
    Approach:
             This problem is solved by Step by Step Procedure:
             
             step 1:Loading a dataset file into the Dataframe
                    
             step 2:From that file we need to select the population and literate columns for finding Literacy Ratio
    
             step 3:The Literacy ratio is :
             
                                Literacy Ratio = (number of literate people in the region / Population of the region ) * 100

             step 4: In this problem the region selected by the state wise and from that dataset we need 3 columns 
                       those are "State name", "Population", "Literate" for calculating literacy ratio
            
             step 5: then grouping above columns of dataset by State name will get all the each states sum of population and literate

             step 6: applying literacy ratio formula to those two columns population and litearte and store it in new column called 
                        literacy ratio
                        
             step 7: after finding literacy ratio we need to plot geographical map for the low iteracy states, but i didn't get the exact
                     longitude and latitude values for writing map, so i plotted a bar graph with first 10 low iteracy values
             

2. Find out most similar districts in Bihar and Tamil Nadu. Similarity can be based on any of
the​ ​columns​ ​from​ ​the​ ​data.

    Approach:
             This problem is solved by Step by Step Procedure:
             
             step 1: Loading a dataset file into the Dataframe
             
             step 2: From that file we need to select the columns those belongs to States of BIHAR and TAMIL NADU from the Dataset
             
             step 3: From this new dataframe we can take any column  to find the similarity between districts of BIHAR and TAMIL NADU
                        so as i choosen Literate for finding the similarity of district between the both states
                        
             step 4: after choosing column as literate the we need to iterate the rows over the two dataframes
             
             step 5: for finding similarity between two datframes of columns values we assume to assume that some value that
                        lies between the those two datframes values of  literate columns
                        
             step 6:then we need to create extract the column values of district and Literate from the above dataframes 
             
             step 7: will get  two dataframes first one is BIHAR second one is TAMIL NADU, i need to plot the graph of those
                         districts similarity from two datframes , for that first i created empty dataframes then i did
                         concatenation of two datafarames
                         
             step 8: from above dataframes  plotted graph with similarity between the two states of districts.
             
             
3. How does the mobile penetration vary in regions (districts or states) with high or low
agricultural​ ​ workers?
    
    Approach:
             This problem is solved by Step by Step Procedure:
             
             step 1: Loading a dataset file into the Dataframe and from that selectig required data for solving this problem.
             
             step 2: we need to find percentage of agricultural workers from total workers with low or high conditions on some
                         specified values.
             step 3: then here selected high values ( assumption = 40 ,for above 40) will get more values for 
                        ploting graph 
                        
             step 4: for finding mobile penetration we need an column values of Households_with_Telephone_Mobile_Phone, Households,
                        mobile penetration = (Households_with_Telephone_Mobile_Phone / Households)* 100
                        
             step 5: after finding mobile penetration we get mobile penetration across states with high agricultural_workers.
             
             step 6: plot graph for the mobile penetration across states with high agricultural_workers.
             
