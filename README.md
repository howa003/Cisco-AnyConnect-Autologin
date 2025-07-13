# Cisco-AnyConnect-Autologin
Batch script for automatic login into a VPN using Cisco AnyConnect.

## Description
There are two scripts - one for connecting, and one for disconnecting.
Both scripts also show you your current IP after the connection / disconnection so you can verify that the operation was successful.

## Initial required configuration
Before using the script, you need to edit your VPN configuration in "src/private_config.login_info".

If your VPN requires different steps to connect, you can find these steps (and appropriately modify the private_config.login_info file) using this approach: https://stackoverflow.com/a/64300886/11875147

## Initial optional configuration
If your Cisco AnyConnect is installed in any other folder than "C:\Program Files (x86)\Cisco\Cisco AnyConnect Secure Mobility Client", you need to manually edit the path in the "src/connect_script.bat" and "src/disconnect_script.bat" files.

## Usage
Run connect.bat or disconnect.bat.
