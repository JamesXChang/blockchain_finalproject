# CS5363 Blockchain Technologies and Applications: Hw8 – DAPP

- how to use
for detail please see the report

##### 學生 張峻騰 105062314
=============================================

## How to use 

URL: https://farmchain.herokuapp.com/

- Give me the address on Ropsten Testnet, and Admin add you as farmer so you can start,
- otherwise you only can check the data(please see 105062314-HW8.pdf)
- 

### Functions 

## Planting:
    Farmer can start planting and upload the planting data like temperature, water volume, sun hours, also can harvest the plant by index.
    Both of user and farmer can access plant data by index
## Warehouse:
    Farm can upload the warehouse temperature.
    Both of user and farmer can access warehouse data (include temperature and stock) by index
## Cold Chain Logistics:
    Admin can upload the Cold Chain Logistics temperature, and the farmer can start the shipment of some order.
    Both of user and farmer can access Cold Chain Logistic data (include shipment date and temperature) by index
## Order:
    User can order the product here, and get the info of product. when the product arrival, user can click the arrival button.
## Delegate:
    Admin can delegate the farmer.

### Local test

# Meteor 
- https://magicalee.github.io/2017/10/26/blockchain-09/#dapp
- follow the tutorial and create a folder(like image.jpg)
- paste my files into client (like image2.jpg), note that static.json should be at the root(outside of client)
- On termainal, cd the the DApp folder(this folder), and type "meteor", you can start running in local

- if you want to change the contract, change the ContractAddress in main.js


