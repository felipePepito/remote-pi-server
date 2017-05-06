# Remote Pi Project - Server Application

## Aims of the project

Creating an interface to remotely control the raspberry pi Pins and retrieve information from sensors.

## Server Application

The Server retrieves and stores data from the raspberry pi and its sensors,
and makes the data available to clients connected to the server.
Moreover, it forwards requests like changing the state of pins
from the client to the raspberry pi.

## Usage

Make sure to adapt the `config-template.json` file to your needs and rename it to `config.json`.
