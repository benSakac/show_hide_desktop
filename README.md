# show_hide_desktop
Bash script to show/hide desktop. Developed to use with hot corners on elementaryOS 

Dependencies: wmctrl

To install wmctrl: 
    
    sudo apt install wmctrl
    
To use with elementaryOS hot corners:

1) Download the script and save it your preferred location
2) Open System Settings
3) Desktop > Hot Corners
4) Pick the corner you want to use for showing/hiding desktop. 
5) Open the drop down menu for that corner and select "Execute custom command"
6) In the custom command field input:

        bash /Path/to/script/show_hide_desktop
    
Ta-da! Your hot corner will now show the desktop if any windows are open or will open minimized windows if the desktop is visible. 

