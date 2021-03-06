# Xbox Remote Power

This is a little script that can turn your Xbox One on remotely.

## Prerequisite

You need three things for this to work:

- Python 2 or 3 installed
- IP address of your Xbox One
- Live device ID of your Xbox One

To find the IP of your Xbox, go to Settings -> Network -> Advanced settings.

To find your Live device ID, go to Settings -> System -> Console info.

## How to use

Run the script as follows, replacing [ip address] with the IP of your Xbox One and [live device id] with your Live device ID.

```bash
python xbox-remote-power.py -a [ip address] -i [live device id]
```

From the Script plugin interface, you can use it like this by creating an "Xbox On" command :

1. Give a name to the command
2. Define the command as "Action"
3. Set the command script with the arguments

![Xbox On command in Jeedom](../images/XboxOnCmd.png)

You can also use variables :
![Xbox On command with variables in Jeedom](../images/XboxOnCmd_with_variables.png)

## FAQ

### All parameters are ok but it doesn't work. Why?

Your Xbox One have to be in "Instant On" mode. More information on <https://support.xbox.com/fr-FR/xbox-one/console/learn-about-power-modes>
