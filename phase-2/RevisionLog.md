# List of changes

## Non-functional requirement

1. Add non-functional requirement “Customer National ID Card must be verified by Administrator ''. This  non-functional requirement has been added because we want the customer national id card to be verified by our administrator due to the register process.

## Requirement prioritization

1. Add “Customer National ID Card must be verified by Administrator '' Requirement prioritization as priority number 2.

## Use Case

1. Connect Register to application use case to Administrator team. This use case has been connected because checking the national id card of the customer occurs during the registration process. 
2. Connect Track money use case to Foundation. This use case has been connected because the foundation not only sends the money status but also can update the tracking report which is in the Track money process.
3. Remove Receive Technical Issues use case from Administrator team. This use case has been removed because the Receive Technical Issues use case occurs during the Report Technical issues process.
4. Connect Report Technical issues to Administrator team. This use case has been connected because the Administrator team is working on the Report Technical issues process.
5. Remove Developer team actor. This actor has been removed from the diagram because this actor has been considered to merge into the Administrator team.
6. Remove Manager team actor. This actor has been removed from the diagram because this actor has been considered that is not necessary.
7. Rename Inventory staff actor to Inventory Team actor.This actor has been removed from the diagram because this actor has been considered to merge into the Administrator team.

## Functional decomposition diagram

1. Create Functional decomposition diagram from data flow diagram level 0,1 and 2.
2. Add dark blue color to the top entity as a process on data flow diagram level 0 because  the different colors on the process level will show the priority of the process.
3. Add orange color to the sub entity as a process on data flow diagram level 1 because  the different colors on the process level will show the priority of the process.
4. Add green color to the sub-tark as a process on data flow diagram level 2 because  the different colors on the process level will show the priority of the process.

![Alt text](https://github.com/ICT-Mahidol/2020-ITCS371-2-MilkTea/blob/main/functional_decomposition.png?raw=true "1")

# Data Flow Diagram

## DFD Level 1

![Alt text](https://github.com/ICT-Mahidol/2020-ITCS371-2-MilkTea/blob/main/DFD%20Level%201.png?raw=true "1")

1. Create Data flow diagram level 1. This data flow diagram level 1 has been created because we would like to clarify more about data flow diagram level 0.
2. Add Customer Entity. This entity has been added because the customer is one of the actors in the use case diagram.
3. Add Foundation Entity. This entity has been added because the foundation is one of the actors in the use case diagram.
4. Add Commercial team Entity. This entity has been added because the commercial team is one of the actors in the use case diagram.
5. Add Administrator Entity. This entity has been added because the administrator is one of the actors in the use case diagram.
6. Add Marketing team Entity. This entity has been added because the marketing team is one of the actors in the use case diagram.
7. Add Inventory team Entity. This entity has been added because the inventory team is one of the actors in the use case diagram.
8. Add Register New Customer process. This process has been added because this is the process that customers create their profile which contains name, address, national id card, and bank account which the data will be stored in the customer detail.
9. Add Donate process.This process has been added because this will be the process that customers donate the money to our company and foundation.
10. Add Show Foundation Information process. This process has been added because customers would like to see the foundation information before choosing them and donate their money to them.
11. Add Report amount of money process. This process has been added because the foundation would receive the money that they deserved and know the amount of money that they would have to update their goal money.
12. Add Report Technical Issue process. This process has been added because this process is one of the functional requirements which customers could report the problem to the administrator.
13. Add Order product process. This process has been added because customers will order the product though this process.
14. Add Send Tracking report process. This process has been added because there is a track money use case which the customer would like to get the update about the money status when do payment in donation, shopping and gaming.
15. Add Log in process. This process has been added because customers must log in to do most activity in the PETMe which the data of username and password will be stored in the customer detail too.
16. Add Top-up Account process. This process has been added because customers can add money to their account in PETMe.
17. Add Play Gashapon Game process. This process has been added because there is a game function which provides for the customers who would like to play the gashapon.
## DFD Level 2

![Alt text](https://github.com/ICT-Mahidol/2020-ITCS371-2-MilkTea/blob/main/DFDlv2.png?raw=true "1")

18. Create Data flow diagram level 2. This data flow diagram level 2 has been created because we would like to clarify more about data flow diagram level 1.
19. Add a few steps to be processed in DFD level 2 . These processes have been extended from the DFD level 1 processes to be more detailed and clear.
20. Add payment step process to the order product process. This process has been added because customers could make the payment after finding their product and ordering them.
21. Add Check the national id card step process to the register to application process. This process will make the administrator verify the customer national id card to identify the customer which is their own or their true national id card or not.

## ERD

![Alt text](https://github.com/ICT-Mahidol/2020-ITCS371-2-MilkTea/blob/main/ERD.png?raw=true "1")

1. Create an Entity Relationship Diagram based on the data flow diagram.

## The VDO recording of presentation

https://drive.google.com/file/d/11aRG-6oGEFIsu6deUc01Jj_Rva-dP_FM/view?usp=sharing
