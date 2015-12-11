
# IpaExporter
  IpaExporter is a plugin for Xcode. The plugin can export the IPA file from the archive in the Organizer window.

  ![image](https://github.com/poboke/IpaExporter/raw/master/Screenshots/tutorial.gif)

  If you want to export the IPA file from the archive, you can open the Organizer window, click the "Plugins" menu, and click the "Export Ipa..." sub menu.

## Supported Xcode Versions
  - Xcode6
  - Xcode7

## Auto Install
  Using [Alcatraz](https://github.com/mneorr/Alcatraz)

## Manual build and install
  - Download source code and open IpaExporter.xcodeproj with Xcode.
  - Select "Edit Scheme" and set "Build Configuration" as "Release"
  - Build it. It automatically installs the plugin into the correct directory.
  - Restart Xcode. (Make sure that the Xcode process is terminated entirely)

## Manual uninstall 
  Delete the following directory:

  `$HOME/Library/Application\ Support/Developer/Shared/Xcode/Plug-ins/IpaExporter.xcplugin`

## License
	(The WTFPL)
	
	            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
	                    Version 2, December 2004
	
	 Copyright (C) 2015 Jobs (www.poboke.com)
	
	 Everyone is permitted to copy and distribute verbatim or modified
	 copies of this license document, and changing it is allowed as long
	 as the name is changed.
	
	            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
	   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION
	
	  0. You just DO WHAT THE FUCK YOU WANT TO.

