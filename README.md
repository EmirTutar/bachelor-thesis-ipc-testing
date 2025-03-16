# Patient Monitoring System with Computer Vision
This repository is dedicated to the development of a patient monitoring system for hospitals, utilizing computer vision to detect potentially dangerous situations such as falls, unusual movements, or the risk of pressure sores.

<p align="center">
  <img src="./doc/documentation/images/overview.png" />
</p>


The primary objective of this project is to implement  soem key functionalities outlined by P. Kittipanya-Ngam, O. S. Guat, and E. H. Lung in their paper titled "Computer vision applications for patients monitoring system," presented at the 2012 15th International Conference on Information Fusion in Singapore (pp. 2201-2208). One such critical feature involves triggering an event if a bed remains unoccupied for an extended period or if an a person has fallen down.

## Getting started
To get this project up and running on your local machine for development and testing purposes, please follow these steps:
1. Clone the repository to your local machine using `git clone <repository-url>`.
2. Ensure that all external dependencies listed below are properly installed.
3. Follow the build dependencies instructions to set up the development environment.
4. Ensure you have credentials set. See the Gitlab - Wiki for all credentials needed.

## External dependencies
- [NVIDIA Docker Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html)
- [Docker](https://www.docker.com/)
- [Docker-Compose](https://docs.docker.com/compose/)

## Runnig the system
Running the system can be done with the following commands:
```bash
cd repo/source
docker compose up
```
Most likely, this command will fail because you have not set up the environment according to our [wiki](https://fbe-gitlab.hs-weingarten.de/stud-iki/prj-sysadmin/ss24_tutar_kleiser_metzler_AAL_Patientenmonitoring/-/wikis/home).

The system requires the following containers to fully function:
- Mailcow
- MQTT
- Alarm
- Mail-Client
- Yolov5
- Matrix
- Matrix-Bridge

## Authors
| Name | Email | Matrikelnummer |
| ------ | ------ | --- |
| Emircan Tutar    | emircan.tutar@hs-weingarten.de    | 35606 |
| Niklas Kleiser   | niklas.kleiser@hs-weingarten.de   | 35579 |
| David Metzler    | david.metzler@hs-weingarten.de    | 35582 |


## License
This project is licensed under the MIT License.

## Problems and solutions
For a detailed list of common problems encountered during the development of this project and their solutions, please refer to our LaTeX documentation found in the [project repository](doc/documentation). A compiled version of the documentation can be found as an [artifact](https://fbe-gitlab.hs-weingarten.de/stud-iki/prj-sysadmin/ss24_tutar_kleiser_metzler_AAL_Patientenmonitoring/-/artifacts).
