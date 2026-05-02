# Ubuntu Desktop on EC2 with VNC

## Goal
Set up a lightweight Ubuntu desktop environment on an EC2 Ubuntu Server instance and connect to it remotely using VNC.

## Environment
- Cloud: AWS EC2
- OS: Ubuntu Server
- Desktop: XFCE / Ubuntu Desktop
- Remote access: VNC

## Steps
1. Create a new Linux user
2. Add the user to sudo group
3. Install desktop environment
4. Install and configure VNC server
5. Open required security group port
6. Connect from local machine

## Notes
This setup was used for testing remote GUI access and running development tools on a cloud instance.
