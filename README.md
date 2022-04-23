# -times-today
 FileReadLine( "count.ini" )     $count = $count + 1     FileDelete("count.ini")     FileWriteLine( "count.ini", $count )     Do     WinActivate("bot-testing - Discord")     Sleep( 50 )     Until WinActive( "bot-testing - Discord" )     Send("I've thought about you " &amp; $count &amp; " times today!")     Send("{ENTER}")     EndFunc
