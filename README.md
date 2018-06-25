#Angular 6

##Installation :

###1. nodejs check, should be > 8
	node –v [v10.4.1]
###2. npm check
	npm –v [6.1.0]
###3. Install Angular Cli
	npm install -g -f @angular/cli  [If this fails on MAC try below steps]
		1. npm cache clean
		2. npm uninstall -g angular-cli
		3. npm install -g angular-cli

###4. Check Angular CLI
	PRASHSR2-M-20SX:angular4-basics-app prashsr2$ ng -v

     _                      _                 ____ _     ___
    / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
   / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
  / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
 /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                |___/


Angular CLI: 6.0.8
Node: 10.4.1
OS: darwin x64

###5. Create new project
		1. ng new angular6-basics-app --style=scss --routing
		2. cd angular4-basics-app
		3. ng serve -o