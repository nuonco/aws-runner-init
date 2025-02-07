# AWS Runner Cloudformation Init

This repository contains the UserData script executed on instance first boot by runner EC2 instances, when the user installs a Nuon-managed app via a CloudFormation quick-create link.

The script installs docker and the cloudwatch agent, then sets up a systemd service that fetches the latest image of Nuon's runner and sets it to restart always.
