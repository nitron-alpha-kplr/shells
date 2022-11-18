# shells
A little script for generating common revshells fast and easy. 

## To install
	git clone https://github.com/4ndr34z/shells
	cd shells
	./install.sh


### Screenshots

![screenshot1](https://github.com/4ndr34z/shells/blob/main/screenshots/macos142.png?raw=true)
![screenshot2](https://github.com/4ndr34z/shells/blob/main/screenshots/shells2.png?raw=true)
![screenshot3](https://github.com/4ndr34z/shells/blob/main/screenshots/shells3.png?raw=true)
![screenshot4](https://github.com/4ndr34z/shells/blob/main/screenshots/shells4.png?raw=true)
![screenshot5](https://github.com/4ndr34z/shells/blob/main/screenshots/upload.png?raw=true)


### Version 1.4.2
- PowerShell: Added a new "mini AMSI-bypass". (It is a partial bypass) Based on Matt Graebers Reflection method 
- PowerShell: Added a "upload" function in the Powershell reverseshell

### Version 1.4.1
- Removed AMSI. Not tested enough :-)


### Version 1.4
- Added AMSI-bypass for the powershell payloads

### Version 1.3.9
- Fixed bug when setting port
- Changed default port to 443
- PowerShell: obfuscated some more


### Version 1.3.8
- PowerShell: Minor changes to the UDP payload


### Version 1.3.7
- Using only native nc on macOS, because the one on homebrew doesn't work on incoming UDP
- PowerShell: Added UDP payloads


### Version 1.3.6
- PowerShell: Added more payloads


### Version 1.3.5
- PowerShell: Added some randomization and obfuscation for the payload


### Version 1.3.4
- PowerShell: Using UTF8 encoding in payload


### Version 1.3.3
- Added Golang


### Version 1.3.2
- Added OpenSSL


### Version 1.3.1
- Fixed bug in Python revshell
- Added awk
- Added Bash UDP 


### Version 1.3
- Added Windows Python revshells


### Version 1.2.9
- Added a ngrok running-status


### Version 1.2.8
- Hiding ngrok choice if not installed


### Version 1.2.7
- Fixed the install options: not doing default option when pressing enter without making a choice


### Version 1.2.6
- Added support for ngrok. 


### Version 1.2.4
- Added a install-script
- Added install options for checking and installing missing dependencies


### Version 1.2.3
- Added a couple of PHP shells


### Version 1.2.2
- Added shells for: Ruby, Perl, Telnet and zsh


### Version 1.2.1
- Added copy to clipboard using pbcopy on macOS
- Added info about listening netcat as the macOS versions doesn't display that


### Version 1.2
- Added looping netcat shells. Calls back every 10 seconds. Great in case you loose your shell
- Added check for netcat GNU netcat 0.7.0 Homebrew when running on macOS


### Version 1.1
- Added support for macOS
