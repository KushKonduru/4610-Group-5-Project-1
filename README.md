
# Team 5 Mist 4610 Group Project 1




## Team Name:


71552 Group 5
##  Team Members:

1. Brian Michaels
2. Kush Konduru
3. Peirece Jennnings
4. Simran Kansara
5. Rohan Reddy

## Problem Description: 


This new boutique fitness studio needs a relational database model to keep track of its business operations. This database must efficiently manage data regarding memberships, respective trainers, and class capacity to meet consumer needs. In addition, the model must reflect internal processes including suppliers for new equipment and enrollment to prevent exceeding physical capacity. Without a structured system, the boutique may overbook classes, order new equipment from the inappropriate supplier, and overall fail to meet consumer needs, resulting in a decrease in revenue. By building this data model, we seek to minimize these disruptions by building a variety of entities with sample data in each table. Entities and their relationships with one another represent the direct concepts the boutique focuses on. By writing queries to test our model, we ensure that this relational database reflects an accurate system for the business boutique.  


## Data Model:

![Fitness Studio Data Model](Images/FitnessStudioModel.png)


## Data Dictionary:

![Fitness Studio Data Model](DataDictionary1.png)

![Fitness Studio Data Model](DataDictionary2.png)

![Fitness Studio Data Model](DataDictionary3.png)

![Fitness Studio Data Model](DataDictionary4.png)

![Fitness Studio Data Model](DataDictionary5.png)

![Fitness Studio Data Model](DataDictionary6.png)

![Fitness Studio Data Model](DataDictionary7.png)



## Queries: 



Query 1: Which trainers have managed more than 10 total attendees across all their classes?

Justification: This identifies top-tier talent. By joining tables and using aggregate functions, management can see who is driving the most studio volume.

![Fitness Studio Data Model](Query1.png)

Query 2: List all equipment purchased more than three years ago that is located in high-temperature rooms. (high temperature > 75 degrees)

Justification: Heat and heavy use can accelerate equipment wear. This query acts as a proactive maintenance tool to prevent injury or unexpected repair costs by identifying gear likely to fail

![Fitness Studio Data Model](Query2.png)

Query 3: Which guest passes are expiring within the next 3 days?

Justification: These guests represent the warmest leads for the sales team. Managers can use this list to trigger a "final offer" or follow-up call to convert the guest into a full member before they leave the studio ecosystem.

![Fitness Studio Data Model](Query3.png)

Query 4: Which studio rooms are currently hosting classes that are at or near their maximum capacity?

Justification: If certain rooms are consistently at 100% capacity, it indicates a missed opportunity for revenue. Management might consider expanding those rooms or moving high-demand classes to larger spaces (square footage).

![Fitness Studio Data Model](Query4.png)

Query 5: List the studio’s suppliers in the order of quantity of equipment provided to our studio?

Justification: Over-reliance on a single supplier can be a business risk if that supplier faces delays or price hikes. This helps management diversify their vendor list for better bargaining power

![Fitness Studio Data Model](Query5.png)

Query 6: Identify the members of the studio that are not currently in a membership

Justification: Members who are not currently paying for a membership are an easy target for revenue-growth. If they have paid for a membership in the past and need to renew for another year, they should be a priority for retention.

![Fitness Studio Data Model](Query6.png)

Write a query to list the number of total classes the fitness studio offers for each category.

Justification: A fitness studio manager would benefit from knowing the number of classes offered per category because it provides a clear snapshot of whether the studio's schedule is balanced and aligned with member demand. If certain categories are over- or under-represented, the manager can make informed decisions about adding, removing, or redistributing classes to better serve the membership base. This insight also supports staffing decisions, ensuring that trainer specialties and availability are proportionate to the volume of classes being offered in each category.

![Fitness Studio Data Model](Query7.png)



![Fitness Studio Data Model](Query8.png)

![Fitness Studio Data Model](Query8.png)

![Fitness Studio Data Model](Query9.png)

![Fitness Studio Data Model](Query10.png)

## Database information:


Name of Database: ns_Sp26_71552_Group5

Additional information: Each query listed above is marked in the database using stored procedures which can be called using the following format: CALL TP_Q1();

