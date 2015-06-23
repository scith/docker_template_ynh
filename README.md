Docker for YunoHost: Container's template
----------------------------------------
Warning: This YunoHost app is still in development. Use it at your own risk!

This is a template that will allow you to deploy a Dockerized YunoHost app quickly and efficiently. The container can be started/stopped via the Services menu of YunoHost

Steps to create the app:
- Edit manifest with application specific information,
- Edit the install script with application specific information (app name, repository, command, autostart, home volume, ports to be checked)
- Edit the remove script with the app name,
- Edit `conf/nginx.conf` file to match application prerequisites !IMPORTANT,
- Enjoy...

Live example: TBD