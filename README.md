# AWS Runner Cloudformation Init

This repository contains the UserData script executed on initialization by all runners when installed through a Cloudformation template.

The script installs docker and the cloudwatch agent, then sets up a systemd service that fetches the latest image of Nuon's runner and sets it to restart always.
