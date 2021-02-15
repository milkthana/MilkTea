# 2020-ITCS371-2-MilkTea
## Introduction
Nowadays, many foundations have high costs for about ten thousand to a hundred thousand baht per month. The income of each foundation comes from the people who want to donate, so it isn’t consistent because sometimes the donation comes a lot but sometimes it comes a few. Moreover, some foundations don’t have online platforms that can update news about their foundations or contact such as Facebook, Instagram, or Twitter. In the part of a philanthropist or an animal lover, they want to donate to the foundation, but some foundations don’t have enough online information or not updated or can’t be contacted. Also, the philanthropist may hesitate to donate money to a foundation that doesn’t have much evidence to confirm.

PETMe is a social enterprise that creates a platform to connect people with homeless animal foundations or welfares. PETMe aims to solve the problem of homeless animals and foundations or welfares. The problem is that foundations or welfares must receive a donation but some of them are far away and don’t have any contact for people to connect online. Although, people will see the foundation on media both online and offline. So, this platform will be another way to connect people and foundations together. In the platform, there isn’t only charitable donation also the users can purchase some products and play mini-game. The money after deducting 30% for software maintenance will randomly give to the foundation. The customers that we focus on are the foundation (or welfare) and the client. The foundation can receive the donation through our platform. Also, the clients can donate to the foundation through our platform.

Our business focusing on donations and we clarified into three ways to earn donation money. There are three main features that PETMe focuses on. The first main feature is a donation. In the donation feature, our platform will post the amount of money and items that the foundation wants. The users can select the foundation that they want and each foundation have a financial proof confirmation that comes from the donation to confirm that this foundation will use the donation’s money for the real purpose. The second main feature of our platform is shopping. The users can shop online in our shop and our products have an image of a dog or cat on it. The last main feature that we have is games. The game that our platform provides is the Gachapon game. In the game, the users can pay for coins to receive mascot randomly. If the users spend more coins, the chance that they will get a high-rank mascot (S, A, B, normal, and rarity) will be increase. The foundation will receive the money directly from the donation feature part. However, the money in part shopping and the game will be organized by the financial team. The 30% of income will use for software maintenance and 70% other will send to the foundation randomly. Also, after the payment is successful, the donation money status will be tracked in 48 hours and the evidence will send to the users in 12 hours.

## Functional Requirements

1. The system must allow the user to login and register system.
2. All foundations should have a name, description, financial proof, picture, and amount of goal money.
3. The system must send the donation money status to users.
4. Users can check the tracking status of the money that users donated.
5. Users can top up on their account.
6. All products should have a name, price, and picture.
7. The system should random the mascot in game.
8. The system must allow the users to exchange from money to game's coin.
9. The system will send the invoice to users.
10. The menu should show the label of each feature.
11. The users can report the problems when our application have problems.
12. The users can do a payment via Apple store or Mobile network.
13. The system allow to update the amount of products.
14. The system will support the search box and filters search.
15. The system have shopping cart function.

## Non-Functional Requirements

1. Make our apps easy to use for every age.
2. Before confirm the payment users have to identify themselves such as fingerprint identification. 
3. Make our apps support to users who are color blindness.
4. Make our support foreign languages such as English, Chinese.
5. System should be able to send donation money status notification to 10 users at least in 1 sec.
6. The application load time should not be more than 1 sec for users.
7. The system should be keeping back ups of all information to the database in every second.
8. Make application support for every OS, Such as IOS ,Android and Linux etc.
9. The users can switch theme into dark mode and light mode.
10. Restore the users previous activities when the system crashes.
11. Customer National ID Card must be verify by Adminstrator

## Requirement prioritization
|Name                                                                                             |Types                      |Req. Priority|
|-------------------------------------------------------------------------------------------------|---------------------------|-------------|
|The system must allow the user to login and register system.                                     |Functional Requirements    |1            |
|The system must send the donation money status to users.                                         |Functional Requirements    |1            |
|The system must allow the users to exchange from money to game's coin.                           |Functional Requirements    |1            |
|The menu should show the label of each feature.                                                  |Functional Requirements    |1            |
|User can report the problems when our application have problems.                                 |Functional Requirements    |1            |
|Make our apps easy to use for every age.                                                         |Non-Functional Requirements|2            |
|Updates the charity event feedback on dashboard apps.                                            |Non-Functional Requirements|2            |
|Add more function in our apps no only donation ,shop and game.                                   |Non-Functional Requirements|2            |
|Customer National ID Card must be verify by Adminstrator                                         |Non-Functional Requirements|2            |
|Add the map for the Charity event to easy to go.                                                 |Non-Functional Requirements|3            |
|Make the application to communicate with others when they choose to go to the same charity event.|Non-Functional Requirements|3            |
|                                                                                                 |                           |             |

## Actor

User

Commercial team

Inventory staff

Marketing team

Foundation

Administrator team

## Use case diagram
![Alt text](https://github.com/ICT-Mahidol/2020-ITCS371-2-MilkTea/blob/main/Usecase.png?raw=true "1")

## Use case narative

1. Donate money

| Use Case: | Donate money |
| --- | --- |
| Iteration: | 1, last modification: October 29 by Jettawat |
| Primary actor: | Customer |
| Goal in context: | To donate money from user to the foundation |
| Precondition: | The customer has to select the foundation that the user wants to donate to. |
| Trigger: | Every money from users must go to the foundation. |
| Scenario: | 1.The customers log into the system.|
||2. Customers select foundations to donate to.|
||3. Customers select payment methods that users want to use.|
||4. If the donation is successful then customers will receive a bill.|
||5. The system will turn to the page which the customers can select the foundation to donate to.
||6. If customers want to donate to another foundation, they can scroll to find the foundation that they want. |
| Exceptions: | 1. The customers must have an account; see in the use case **register application**.|
||2. Banks systems will be closed; see in use case **do payment**.|
||3. The customers must have an account to donate to the foundation; see in use case **register application**. |

2. Purchase products

| Use case: | Purchase the products in the system. |
| --- | --- |
| Iteration: | 1, Start modification: November 1, 2020, by Thanyarat. |
| Primary actor: | Customer |
| Goal in context: | To get the product that customers have selected. |
| Precondition: | The customer has to select and check the products; price, quantity, description. |
| Trigger: | The money from shopping can donate to the foundation directly. |
| Scenario: | 1. Customers log in to the system.|
||2. Customers select **shopping** on the label in the application.|
||3. Customers scroll to find the products that users want.|
||4. Customers select the product, then add to carts.|
||5. Customers can select the quantity of the product.|
||6. Customers can select payment methods to pay for the products.|
||7. The system will receive the orders from the customer and check the products in the system. |
| Exceptions: | 1. The customers must have an account; see in the use case **register application**.|
||2. The bank system will be closed; see in the use case **do payment**.|
||3. The system didn&#39;t update the products; see in the use case **updated products**. |

3. Track money

| Use Case: | Track money |
| --- | --- |
| Iteration: | 1, last modification: September 28 by Suphanat. |
| Primary actor: | Customer |
| Goal in context: | To update the donation money status. |
| Precondition: | Do a payment in donation, shop, and game. |
| Trigger: | The customer should know that the donation money has arrived at the foundation or not. |
| Scenario: | 1. A customer logs in to the system.|
||2. The customer selects the **tracking** label.|
||3. The customer selects the foundation that the customer wants to see tracking.|
||4. The status of money shows up.5. If the status is complete, the customer will receive the thank you message.|
||6. The customer opens the message up. |
| Exceptions: | 1. The customer must have an account; see in the use case **register application**.||
||2. The system doesn&#39;t show the status; see in the use case **manage information**. |

## Functional decomposition diagram

![Alt text](https://github.com/MilkTea/blob/main/functional_decomposition.png?raw=true "1")

## DFD

### DFD Level 1

![Alt text](https://github.com/MilkTea/blob/main/DFD%20Level%201.png?raw=true "1")

### DFD Level 2


![Alt text](https://github.com/MilkTea/blob/main/DFDlv2.png?raw=true "1")

## ERD

![Alt text](https://github.com/MilkTea/blob/main/ERD.png?raw=true "1")

## The VDO recording of presentation

https://drive.google.com/file/d/11aRG-6oGEFIsu6deUc01Jj_Rva-dP_FM/view?usp=sharing
