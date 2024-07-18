# JableTV Download WebUI

JableTV Download WebUI is a user-friendly web interface for downloading videos from [jable.tv](https://jable.tv/). This project is built on top of [hcjohn463's JableTVDownload project](https://github.com/hcjohn463/JableTVDownload). 

## Demo

## Installation

- Clone this repository: 

``` bash
git clone --recurse-submodules git@github.com:ihainan/JableTVDownload-WebUI.git
```

- Modify the docker-compose.yml file:
    - Change `./downloads` to the path where you want to save downloaded videos.
    - Change `./docker-test/db` to the path where you want to save the database file.
    - Optionally, modify the `ENCODING_TYPE` environment variable. Check [this Python script](https://github.com/hcjohn463/JableTVDownload/blob/main/download.py) for more details about the encoding types.
- Start the Docker services: 

``` bash
docker-compose up -d
```
- Access the web interface by navigating to http://<ip_address>:41056 in your web browser.

## Acknowledgments

Special thanks to [hcjohn463](https://github.com/hcjohn463) for the [original JableTVDownload project](https://github.com/hcjohn463/JableTVDownload/tree/main), which serves as the foundation for this project.



