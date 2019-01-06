# Project Name
KnowYourFood

## Description

Problem Statement:
Right now the deterioration in quality of food and food supply chain is caused by addition of unwanted chemicals by the farmers or transporters, the degradation by suppliers or manufacturers or the adulteration by local vendors and restaurants leads to the cost of life of thousands. The aim is to minimize these adulteration activities and scams thereby saving lives in a cost effective manner.

Idea/Solution:
We aim to use an distributed ledger to record each stage of food cycle, right from the seeds sown in farm to the delivery of final product. We tend to integrate IoT sensors to record food conditions in the ledger at different areas like farms, transportation vehicles, warehouses, factory, etc which would be publicly accessed by organizations such as fssai to regulate the quality of food. Transactions related to business & finance between two parties are kept private. If adulteration occurs at any stage, we can trace its path to source through the ledger and dismiss the guilty.

## Functions
1. It allows the farmer to set all the crop related information and the market to which the food is to be delivered.
2. A classification is done on the basis of seed grade and the fertilizer grade purchased by the farmer.
3. This application empowers the customer to know exactly where their food comes from and what growing conditions.

## Use case diagram link
https://drive.google.com/open?id=11jdg4vit5eLnNIJ_UhJzHURO0fpOwKrx

## Technology stack / technology used ( Very Detailed )

Ganache: 
Ganache CLI, part of the Truffle suite of Ethereum development tools, is the command line version of Ganache, your personal blockchain for Ethereum development.
Ganache CLI uses ethereumjs to simulate full client behavior and make developing Ethereum applications faster, easier, and safer. It also includes all popular RPC functions and features (like events) and can be run deterministically to make development a breeze.

Node.js: 
Node.js is an open-source, cross-platform JavaScript run-time environment that executes JavaScript code outside of a browser. JavaScript is used primarily for client-side scripting, in which scripts written in JavaScript are embedded in a webpage's HTML and run client-side by a JavaScript engine in the user's web browser.

Ethereum: 
Ethereum allows the user to write smart contracts and deploy them on the ethereum blockchain.

Solidity: 
Solidity is the language used to write smart contracts on the Ethereum network. Using solidity we have created a contract which allows the Farmer to set and get information related to the crop and the details of the market in which the crop is to be sent. Then an algorithm classifies the food on the basis of the seed grade and the fertilizer grade. Finally, it returns the result to the customer.

IoT/Python/MQTT: 
This is used to use the sensors for the nutritional grading of soil.We make use of a microprocessor called the Raspberry Pi 3 which is the main connector to the sensors and the Internet. Python and RPi.GPIO are used to code the sensors so that the sensors provide edge services. MQTT which is the message queuing telemetry transport protocol, that is used to provide the messages from the sensors to the subscribed user.

MetaMask: 
Metamask is a cryptocurrency wallet which can be used on the Chrome, Firefox and Brave browsers. It’s also a browser extension.

## Limitations
1. Maintaining and controlling the IoT sector dynamically in the system is difficult i.e. maintaining the edge services of IoT. Using dummy sensor and dummy output data for the current display.
2. Integrate with food authorities like fssai to regulate and maintain the quality of food.
3. Enforcing strict punishment for the guilty farmer and retailer.
4. Multiple array returning is not supported by Solidity.

## Future Aspects
1. Sensors play an important role in determining additional data values throughout the entire food supply chain.
Starting from the farms, which is keeping a track of all the environmental conditions of the crop growth (humidity, temperature, soil, chemical, gas and more sensors), can give us additional information about the lifestyle of the crop growth which can further be used for research and nutritional grading analysis.

2. Image processing, smart cameras, weight sensors and an integration of GPS & Road Conditional system for a location can be used in order to automize transportation and delivery. This means that we can track the route of the delivery vehicles, image processing and camera to keep a check of the security while the delivery. This could also find out reasons of the crop damage in such cases, using the route used by the vehicle (Noting the road conditions). And finally, weight sensors to dynamically send an alert that the rash driving in causing the loss of crop because of loose containment.

3. Agricultural scientists are researching on the dielectric food sensors that senses the raw vegetable crops just after harvest.

4. Solidity Languages for smart contracts does not allow returning arrays of arrays because of which we aren’t able to get data from the blockchain for over a period of time and hence we weren’t able to create graphical analysis of specific food crop from specific retailers of a specific locality when requested.

5. One of the most important future aspect is that currently our system deals with a part of the food chain supply where we focus only on the crop transaction between the farmers and the ethical organization (Like Walmart and more) who directly buy from the farms. Further we plan to complete the system by developing more and better functionalities for the transaction of ethical organisations who buy from the crop collection centers (or Mandis) and finally to find a solution for the unorganized part of the food chain (Local Vegetable vendors and Local Grocery Shop) without disrupting the political interference and the Trader Transaction Fee(GST at stages).
6. Our system will finally lead to a fully developed application that will empower the users to get a complete transparency of the entire food chain supply and will get more and more technical information about item( which means that this system enables the users to know the details of the birth of the crop and the complete lifestyle of the crop till it reaches the users).

## github project link
https://github.com/SarveshVirkud/Know_Your_Food 

## Contact info ( emailid - github id )
Team ID: sarvesh.virkud870

1. Sarvesh Virkud (Team Leader): virkud.sarvesh@gmail.com ( https://github.com/SarveshVirkud )
2. Mukund Vora: mukund.0608@gmail.com ( https://github.com/mukund68 )
3. Ayush Ghanekar: ayushghanekar02@gmail.com ( https://github.com/ayushgha )
4. Urvi Bhanushali: urvi01bhanushali@gmail.com (https://github.com/urvi01)
