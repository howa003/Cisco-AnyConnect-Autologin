# Cisco-AnyConnect-Autologin
Batch script for automatic login into a VPN using Cisco AnyConnect.

## Description
There are two scripts - one for connecting, and one for disconnecting.
Both scripts also show you your current IP after the connection / disconnection so you can verify that the operation was successful.

## Initial configuration
Before using the script, you need to edit your VPN configuration in "src/private_config.login_info".

If your VPN requires different steps to connect, you can find these steps (and appropriately modify the private_config.login_info file) using this approach: https://stackoverflow.com/a/64300886/11875147

## Usage
Run connect.bat or disconnect.bat.
