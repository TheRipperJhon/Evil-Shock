## IF WAITING ON US TO UPLOAD THE SCRIPT FILE WAIT WE ARE DEVELOPING IT BUT WE ARE JUST SETTING UP THE GITHUB RESPORITIE! ITS NEARLY DONE

# Evil-Shock Description 
Evil-Shock is a powerful tool made to exploit Shellshock, what's special with Evil-Shock is that it doesn't base his attacks on one parameter, example another tool might inject a simple "echo Vulnerable" and see if the server executes that. In many case the server wont execute that command but can execute another command ;)
Evil-Shock will find the perfect command also known as Injection Point and then execute further commands to gain remote access via the injection point, so far for the first version Evil-Shock can check for 4 different Injection Point:
<p>
1 - NSLookup
</p>
<p>
2 - Echo
</p>
<p>
3 - LS
</p>
<p>
4 - Ping
</p>

In further version more injections points will be added.

# Screenshots / Examples
# Bind Shell / Auto-Point-Injection:
![BindShell Example](https://i.imgur.com/9dVjdQu.png)
# Reverse Shell / Auto-Point-Injection:
# WARNING: MY FIREWALL IS BLOCKING CONNECTION SO I CANNOT SHOW THE REVERSE SHELL BUT IT SHOULD WORK FINE IN ANY ANOTHER CASE :)
![ReverseShell Example](https://i.imgur.com/ZlZcgmR.png)

# Features
Evil-Shock is equiped with some useful and interresting command:

t|target=<target link> : This will set the target.          
shell=<reverse / bind> : This will set the shell type.
p|port=<port> : Port to open the shell on.             
help : Print help menu.             
inject=<string> : This will allow an user to inject a custom command into the web server.          
user-agent=<string> : When info grabbing you can choose to have a custom user-agent or use the default one.        
srv-persistent : When only bind shell is selected and injected this will then injected a persistent backdoor.    
inject-only : This will test Injection Points only, not inject anything else.      
