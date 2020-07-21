#SKHD profile switcher  
  
a script that switches out SKHD configs and pushes a system notification displaying the config that is currently active  
  
##Requirements
requires the $SKHD\_DIR environment variable to be set  
configs must have unique names  
the first line of each config must be a comment containing the config name (e.g. `#Default`). The perviously active script will be stored under that name (without the \#).  
  
##Usage  
`chmod +x switcher.sh`  
`./switcher.sh NEWCONFIGNAME`  






