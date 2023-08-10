---
title: "Mysql deployment"
date: 2022-10-17T09:25:46+05:30
draft: false
---
MYSQL is a widely used, open-source relational database management system (RDBMS).

##### ➡️ This deployment uses the official Mysql Docker image.  

➡️ Go to create apps page and Search mysql on the search bar.

➡️ Click on install button.

➡️ Fill all the reqired feilds.

| PRODUCT NAME  |
| :--------     | 
| `mysql`    |

`PROTOCOL`

| HTTP          | TCP/UDP       |
| :--------     | :--------     |
|    `80`       |               |

➡️ click on Advanced.

| ENV VARIABLE         |  WHITELIST                                                       |        WORKING DIR          |
| :---------           | :--------                                                        |:----------------------------| 
| `Give env variable`  | `If you want to white list any ports list here`                  |`WORKDIR for the application`|

➡️ Click on the Install button.

➡️ You will be redirected to My Apps page, Here you can find all the applications you deployed.

![App Screenshot](images/my.png)

➡️ Copy the mysql application Hostname without NodePort and search the Url. 


## FAQ

#### About mysql image we used.

This is the official mysql image.

#### Are there any restrictions on adding data sources ? 

you can add any data source that mysql supports.
 

#### Are my data persistent ?

For the free user there is no persistence, and for the premium user you can different type of persistence.
