### Kathara for GRID&CLOUD 2019 spring

This project illustrates work with Kathara framework:
https://github.com/KatharaFramework/Kathara

The network is configured using Netkit. Final network layout (can be easily extended):
<img src="https://i.ibb.co/QdLQjjQ/image.png" alt="image" border="0"></a>

Kathara lab configuration:
``` 
Server[0]=A

router1[0]=A
router1[1]=B

router2[0]=B
router2[1]=C

cl1[0]=C

cl2[0]=C

cl3[0]=C
``` 

## Install Kathara
Instructions:
https://github.com/KatharaFramework/Kathara/wiki

## Clone this repo
``` 
git clone https://github.com/vladyan18/Grid_kathara_lab
``` 

## Create directory for user "Kathara"
In Users directiry if your OS is Windows. This is required for solving a possible problem with cyrillic text in the directory names.
Note that Kathara framework was changed by me to avoid problems.

## Start project
``` 
$NETKIT_HOME/lstart
``` 

## Run any client server application
Apache is running on the server. And address 10.0.0.1 respond to requests (across 2 routers).


[![yXBeuV0lA9AhsY4lQOoKXA4fEJo3bAb4RSa8CDDp.gif](https://s3.gifyu.com/images/yXBeuV0lA9AhsY4lQOoKXA4fEJo3bAb4RSa8CDDp.gif)](https://gifyu.com/image/9Rjh)

Now we can observe how the impact on the router affects the user experience:

[![ZtjRbw4iNkKITz7UitrJ9GahFYmi0y43xLe2J45A.gif](https://s3.gifyu.com/images/ZtjRbw4iNkKITz7UitrJ9GahFYmi0y43xLe2J45A.gif)](https://gifyu.com/image/9Rja)

Thus, the Kathara framework is extremely useful for rapid prototyping of networks with different configurations and load simulation.
