# Empatica MATLAB BLE Client
Empatica BLE (Bluetooth Low Energy) Client for MATLAB environment, developed at ICAT, Virginia Tech

This script provides a MATLAB based GUI to communicate with the Empatica Windows BLE Server, whose working is 
described in [http://developer.empatica.com/windows-ble-server.html]. 

This code was developed as a part of a research project that resulted in the following publication, please cite this work if u find it useful:
```
@inproceedings{saha2017affective,  
     title={Affective Feedback in a Virtual Reality based Intelligent Supermarket},  
     author={Saha, Deba Pratim and Martin, Thomas L. and Knapp, R. Benjamin},  
     booktitle={Adjunct Proceedings of UbiComp 2017, ACM Joint Conference on Pervasive and Ubiquitous Computing, Maui, Hawai'i, USA},  
     year={2017},  
     organization={ACM}  
}
```


## How to use:
Pre-requisite: 
It assumes Empatica BLE Server for Windows is already installed. [You can launch the software from this Client GUI]

This script provides the following capabilities:
* Launch the BLE Server software.
* Connect to the Empatica E4 watch in streaming mode [LED glows blue when connected].
* List all the E4 watches connected to Empatica BLE Server and choose which to connect to.
* Choose the data streams to log.
* Log data to file to be saved as sessions in ./data/ folder.
* Live stream and plot data in Matlab (in progress).
* Live Connection/Streaming status 
