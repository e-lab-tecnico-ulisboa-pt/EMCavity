# EM Cavity
This repository contains all the software needed to run the EM Cavity experiment.

## EM Cavity Code
The `EM_Cavity` folder contains all the software developed in the master for this **Deployment of a microwave cavity experiment using the Framework for Remote Experiments in Education**.

Including the test of individual software made for the pressure reader and the spectrum analyser.

## FREE Server
The `cavity_FREE_serve` folder contains all the HTML and JS needed to deploy the experiment page.

## RPi_Proxy
The `RPi_Proxy` folder contains the proxy tool capable of running the experiment and communicating with a 0.6.0 version of the FREE server.

It contains the modification of the EM Cavity code and the `RPi_Proxy/pic_interface/interface.py` so that the proxy is able to execute the function date, has the state machine of the experiment and sends the data to the FREE server.


