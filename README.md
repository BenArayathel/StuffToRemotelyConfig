# StuffToRemotelyConfig
Repository to store information on how to configure my Spring application

Naming Convention is important for configuring our applicaiton (Inside your Boostrap.properties/yml file, spring.application.name = <project-name> must match whatever the names of the configuration file inside of Remote Repository)
  
If none of the names match, only information from application.properties will be referenced. 

If names match, the attributes will be overrided by application.properities, the more narrow scope will override the general scope values. 
