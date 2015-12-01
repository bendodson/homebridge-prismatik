# Prismatik plugin for Homebridge

This is a very basic plugin to enable Prismatik support for Homebridge. It allows you to turn Prismatik on and off and set the brightness as a percentage. To use with Homebridge, you'll need to update your config file like so:

	"accessories": [
        {
            "accessory": "Prismatik",
            "name": "Computer",
            "apikey": "key"
        }
    ]

You will need to go to the _Experimental_ tab in the Prismatik software, enable the API server, and set the Key (the code above assumes a Key of "key" and that Homebridge is running on the same machine as the Prismatik software).