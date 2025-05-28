# Project Name

Cray-Keycloak-users-localize

## Description

This chart runs the keycloak-setup docker image from [keycloak-installer](https://github.com/Cray-HPE/keycloak-installer) to run the [keycloak_localize.py](https://github.com/Cray-HPE/keycloak-installer/blob/master/keycloak_setup/keycloak_localize.py) script.

### Updating the Docker Image

Please update and create the change in the keycloak-installer repo. Once that is released then
change the chart version, and the app version in the Chart.yaml file. Also update the image
tag in the Values file.

## Contributing

See the [CONTRIBUTING.md](CONTRIBUTING.md) file for how to contribute to this project.

## Changelog

See the [CHANGELOG.md](CHANGELOG.md) for the changes and release history of this project.


## License

This project is copyrighted by Hewlett Packard Enterprise Development LP and is distributed under the MIT license. See the [LICENSE.txt](LICENSE.txt) file for details.
