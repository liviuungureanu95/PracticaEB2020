My Project is called infotainment and control truck.
It is structured in one big menu with submenus:
										- air control
										- truck's commands
										- lights and doors
										- media
										
The main menu includes all above, 2 buttons, one which locks or unlocks the door and the other which activate or dezactivate the brake of engine.
Also there is the start/stop engine. When it is pressed, it will appear a pop-up message which warns the driver that he is on the pause time and the time until
he can drive. Otherwise , it will appear a message that informs the user that it is safe to drive.

Very important: From almost all menus and submenus the user can move the other very easily by pressing one button in the corner of the screen and also 
he can get back to principal menu.
 
	--The air control menu is divided in other 3 submenus.I use a compound state for arranging better these:
															-control of air for chair
															- control for AC in whole truck
															-control of warming for steering-wheel
		(Here there are different buttons,animations,border or coloring effects)
		
	--The truck's controls menu contains an instantiator list of butons (created in photoediting) which let the user to acces
	                                                       -autopilot function
														   -chair control(for moving the chair back,front,upp and down)
														   -bed control
														   -tyres pressure simulation
														   -schedule driving like a personal agenda
      (every function was encapsulated in a specific container , and each will activate by pressing the specific button from instantiaotr list 
	   with help op visible/invisible proprierty)
	   (Here i use the instantiator list as i had already mentioned, some animations,retaining some external values for simulation of some activities, creation of a keyboard which
	   let the user to save a personal intinerary (with help of external datapools), pop-up messages)
	
	--The menu lights and doors contains a 3d object which show the changes of lights (short/full-beam light) or the opening/closing the doors.Also the behaviour of these is saved on some external datapools.
	So , when the user is moving to onether menu or submenu context, the changes of them are saved. 
	
	--The last menu called Media contains control of playlist,music,volume,Bluetooth, and radio submenu. Furthermore,the radio fm-band can be moved with help of "<" ">" buttons and the frequency FM is showed in real time
	on an text-label.

For the big menus it was created a template which contains the buttons which help the user to move through each menu  and also everywhere it is displayed he time and date in real time.(EB has GMT -3. So that's why 
there is another hour different from the system time hour.)
