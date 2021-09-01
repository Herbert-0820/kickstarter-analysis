# Kickstarting with Excel

## Overview of Project

        Louise's play Fever is aiming to crowdfunding campaign to help fund her play, Fever. The play have been devided into 9 parts, sets, costumes, props, makeup, lighting, rehearsal space, advertising, programs, and actors. With a budget over $10,000 for meeting the expense demands for her play, she collected the data sets which includes the campign, the goal, the country, the deadline, outcomes and so on.

### Purpose

        In order to understand the campaign and increase the possibility of the success, the outscomes based on lauch date and the outcomes based on goals have been analyzed. The data will be divided in multidemensions by catagory and subcatagory. The trends will be detected for different catagories. Since this is her first time doing crowdfunding, the analyzed data set will be historical data for the future campaign.

## Analysis and Challenges

        Starting with reading the data and unnderstanding the data set, more cleaning work needs to be done. For instance, the date has been transferred to readable data. The catagory needs to be saparated so that the conclusions will be more accurate.

        Filters, pivot table, countifs and more functions are utilized during the whole process. After the date is transferred, the pivot table is able to fomulated the outcomes based on date. To give more insights of the relation between outcomes and the goal, the goal ranges are assigned to demostrate how outcomes are influenced.

        During the whole analysis, there is no data about the demographics. It is hard to target the group who tends to fund the campaign. Moving forward, it will be more helpful for the campaign to include mroe information about the demographic.

### Analysis of Outcomes Based on Launch Date
        
        First, the date transform function is used to make the date readable
        Second, the use the countifs function to calculate how many sucessful, failed, and cancel fo the dataset
        Third, group the data by successful, failed and canceled by months and filtered by parent catagory and year
        Fourth, insert the pivot chart to observe the trends by filters


### Analysis of Outcomes Based on Goals

        First, set up and input the ranges
        second, countifs function to show number successful, failed, canceld for each range
        Third, sum funcation to calculate the total projects and then do the mate for rates
        Fourth, select the certain columns to insert the pivot table 

### Challenges and Difficulties Encountered

        From the start to use countifs function, I was trying to combine all the conditions together. After seached online, I fnd out that the countifs function has to seprated multi conditions.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
       
        Based on the launch date the theater related campigns, the campagins successfully funded are the most in May. December has the smallest amount of campaigns which are successful. From January to December, the success of the campaign increases fluctuatedly till May and hits the pitch in May. From June, it dropped drmatically.

        The campaigns failed in funding are the most in May and October. March as the smallest amount of campaigns which are field. From January to Decemeber, the failure of the campaign is steady from the start and flucuates since September.

        The cancelled campaigns are smooth and steday during the year.

- What can you conclude about the Outcomes based on Goals?

        Baes on goal, most of the campaigns are sitting in the range from 1,000 to 4,999. The range for over 50,000 has less campaigns than any ohter ranges.The highest successful rate is for range less than 1,000, which has the lowest failure rate and cancel rate at the same time. The lowest successful rate is the campaigns over 50,000, which has the highest failure rate and cancel rate as well.

        As the goal increases, the success rate is slowly dropping, and the cancelling rate is increasing, failure rate is more smooth.

- What are some limitations of this dataset?

        The dataset does not include the demographic information, such as donators' gender, age and so on
        The country column did not specify more detials for different regions, which could influence the outcoems and pledged amount as well


- What are some other possible tables and/or graphs that we could create?
       
        Outcomes based on countries
        Outcomes based on year
        Pledged amount based on Countires
        Pledged amount based on year
        The percentage of pledged amount to the goal based on countries
        The percentage of pledged amount to the gaol based on year