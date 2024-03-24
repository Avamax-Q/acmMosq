# acmMosq

Steps taken
1 install Mosquttio eclipse
  -> 1711284117: Error: Only one usage of each socket address (protocol/network address/port) is normally permitted.
  -> used Telnet to cehck what was running on port 1883, turned it off in Services.msc
2 Allow it through windows Firewall on port (create a exception) 
3 run broker in CMD admin mode
4 run subscriber in another terminal with name of 'topic' (uses default port and local host)
5  run publisher on same topic name in another terminal with a message
