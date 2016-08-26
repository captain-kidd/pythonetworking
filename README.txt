# pythonetworking
Networking tools in Python, to be used by programmers of Python scripts ONLY.
     /""""""""/ /""/  /""/ /""""""""""/  /""/  /""/  /""""""""/  /""""\      /""/
    /  /"""/ / /  /__/  /  """/  /"""   /  /__/  /  /  /""/  /  /  /\  \    /  /
   /   """  / /_____   /     /  /      /  ___   /  /  /  /  /  /  /  \  \  /  /
  /  /"""""" ______/  /     /  /      /  /  /  /  /  /__/  /  /  /    \  \/  /
 /__/       /________/     /__/      /__/  /__/  /________/  /__/      \____/
     /"""/  /"""/  /""""/  """/"""   /"""""   /""""  /""""/  /\    /  /\    /  /""""  /""""/
    /___/  /   /  /____/     /       """""/  /      /____/  /  \  /  /  \  /  /""""  /____/
   /      /___/  /   \      /       _____/  /____  /    /  /    \/  /    \/  /____  /   \
   
   
   Usage:
    1. Install Python if it wasn't installed already
    2. Edit the file in the variable < portList > to add the ports you want, or if you want instead to scan a range of ports
      don't edit portList and continue reading. 
    3. Open a Python shell.
    4. Import the socket module.
    5. Copy the portList variable to your python shell in the case you wish to use a pre-made port list.
    6. Copy the ccheck function to your python shell and hit enter.
    7. Copy the portScannet function to your python shell and hit enter.
    8. Type 
          portScanner(put_scanned_host_here, put_portList_here)
       and hit enter. If you would rather use a range of ports, type
          portScanner(put_scanned_host_here, range(put_beginning_port_here, put_ending_port_here)
       and hit enter.
