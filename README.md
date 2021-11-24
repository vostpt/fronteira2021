# CROWD MANAGEMENT SYSTEM
## 24H TT Vila de Froteira 2021 

This python script creates a dashboard with realtime updates regarding the capacity of spectactor zones (ZE) for the motorsport event **24h TT Vila de Fronteira 2021**

![Fronteira Official Image](https://www.24horastt.com/ResourcesUser/Images/Destaques/ACP-Banner-24H-FRONTEIRA-2021-Cartaz-Oficial-nov-2021.jpg)

## Source

This script is based on the Crowd Management System developed for **Rally Portugal Vodafone** than can be found [**here**](https://github.com/vostpt/rallyapp)

## How to run the script 

- download files or fork this repo to your machine
- create virtuaenv on your machine
- cd to the directory where requirements.txt is located
- activate your virtualenv
- run: ```pip install -r requirements.txt in your shell```

## Datasource file 

The .csv file with the information is updated every minute. 
You can change the update interval by changing the value on line ```261```
You can change the datasource by changing the URL on lines ```18``` and ```267```

## How does it work in real life?
![CMS_Fronteira_trans](https://user-images.githubusercontent.com/34355337/143290712-a632a528-c142-4c1e-a6b0-728b5427a2a0.png)

Authorities in the spectactor zones, and on the roads that give access to those,  relay information to the race control, that updates the capacity in real time. 
At any moment anyone can check the capacity of the spectator zones. 

## Credits 

Developed by Jorge Gomes (Python Script), João Pina (Container and Deployment), Miguel Carreiro (Bot), and Marco Maia (SysAdmin) 


