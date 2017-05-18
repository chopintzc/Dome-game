# **Dome-game**

## **Summary of the project:**

This is the Project for my Technology Innovation class, written in C# and Unity.
It is a system to build dome animation using Unity platform. The animation consists of
introduction to a series of endangered animals. Each animal is assigned with a qr code.
The scan of qr code will send a request to our backend RESTful api written in java spring.
The backend api will return the reqired information for the given animal in JSON format.
Our system then parse the returned JOSN message to get animal name, introduction, location,
and picture. Unity then render the dome with those information with defined layout

## **Requirement**

This program requires C# and Unity 5.4.1

## **Features**
* each animal is assigned a qr code, the scan of qr code will send a request to backend api
* the returned information is in JSON format and need to be parsed to attrieve individual part of animal introduction
* dome is rendered by Unity with defined layout of animal introduction

