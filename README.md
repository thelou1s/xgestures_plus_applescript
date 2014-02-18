xgestures_plus_applescript
==========================

xGestures + AppleScript = Google Chrome SmoothGestures

=

global frontApp, frontAppName, windowTitle

set windowTitle to ""
tell application "System Events"
	set frontApp to first application process whose frontmost is true
	set frontAppName to name of frontApp
	--display dialog frontAppName
	
	if frontAppName = "Google Chrome" then
		tell application "System Events" to keystroke "[" using command down
	end if
end tell

=

global frontApp, frontAppName, windowTitle

set windowTitle to ""
tell application "System Events"
	set frontApp to first application process whose frontmost is true
	set frontAppName to name of frontApp
	--display dialog frontAppName
	
	if frontAppName = "Google Chrome" then
		tell application "System Events" to keystroke "]" using command down
	end if
end tell

=

tell application "System Events" to keystroke "w" using command down

=

tell application "System Events" to keystroke "F" using {shift down, command down}

=

tell application "System Events" to keystroke "0" using command down

!=

tell application "System Events" to keystroke "t" using {command down, 126 down}
