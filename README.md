# Empatica MATLAB BLE Client
Empatica BLE Client for MATLAB environment, developed at ICAT, Virginia Tech

This script gives a MATLAB based GUI to communicate with the Empatica Windows BLE Server as 
described in [http://developer.empatica.com/windows-ble-server.html].

Pre-requisite: 
It assumes Empatica BLE Server for Windows is already installed. [You can launch the software from this Client GUI]

This script gives a user the capability to do the following:
* Launch the BLE Server software.
* Connect to the Empatica E4 watch in streaming mode [LED glows blue when connected].
* List all the E4 watches connected to Empatica BLE Server and choose which to connect to.
* Choose the data streams to log.
* Log data to file to be saved as sessions in ./data/ folder.
* Live stream and plot data in Matlab (in progress).
* Live Connection/Streaming status 
