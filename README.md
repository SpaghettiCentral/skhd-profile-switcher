# SKHD profile switcher  
  
A script that switches out SKHD configs and pushes a system notification displaying the config that is currently active. Since SKHD is able to hotload configs this script can be run to change button layouts on the go.  	
  
## Requirements
For this to work a couple of adjustments to config files must be made. Firstly this script requires the $SKHD\_DIR environment variable to be set.
Secondly all configs must have unique names.
Lastly, the first line of each config must be a comment containing the config name (e.g. `#Default`). The perviously active config will be stored under that name (without the \#). This is also why config names must be unique. 
  
## Usage  
`chmod +x switcher.sh`  
`./switcher.sh NEWCONFIGNAME`  






