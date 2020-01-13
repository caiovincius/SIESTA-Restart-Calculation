# SIESTA-Restart-Calculation
An easy tool to restart your SIESTA Calculation if your machine restart for some reason.

## How to use
- Go to the script folder
- Type in the terminal: crontab -e restart_calc
- Edit the file with your favorite editor, and add the following line at the end: @reboot /PATH/TO/FOLDER/restart_calc
- Save the file
- Reboot your machine to the changes take effect
- Go to the script folder again, copy the file "run" to your new calculation folder
- Open the "run" script with text editor and replace the last line with the correct command to run your siesta calculation.
- After that, type in the terminal: at -f run now
(Every time you want to do a new SIESTA calculation, execute it by using the run script)




