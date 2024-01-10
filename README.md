<!-- DO NOT EDIT THIS FILE MANUALLY -->
<!-- Please read https://github.com/linuxserver/docker-calibre/blob/master/.github/CONTRIBUTING.md -->
[![linuxserver.io](https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/linuxserver_medium.png)](https://linuxserver.io)

[![Blog](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=Blog)](https://blog.linuxserver.io "all the things you can do with our containers including How-To guides, opinions and much more!")
[![Discord](https://img.shields.io/discord/354974912613449730.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=Discord&logo=discord)](https://discord.gg/YWrKVTn "realtime support / chat with the community and the team.")
[![Discourse](https://img.shields.io/discourse/https/discourse.linuxserver.io/topics.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=discourse)](https://discourse.linuxserver.io "post on our community forum.")
[![Fleet](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=Fleet)](https://fleet.linuxserver.io "an online web interface which displays all of our maintained images.")
[![GitHub](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitHub&logo=github)](https://github.com/linuxserver "view the source for all of our repositories.")
[![Open Collective](https://img.shields.io/opencollective/all/linuxserver.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=Supporters&logo=open%20collective)](https://opencollective.com/linuxserver "please consider helping us by either donating or contributing to our budget")

The [LinuxServer.io](https://linuxserver.io) team brings you another container release featuring:

* regular and timely application updates
* easy user mappings (PGID, PUID)
* custom base image with s6 overlay
* weekly base OS updates with common layers across the entire LinuxServer.io ecosystem to minimise space usage, down time and bandwidth
* regular security updates

Find us at:

* [Blog](https://blog.linuxserver.io) - all the things you can do with our containers including How-To guides, opinions and much more!
* [Discord](https://discord.gg/YWrKVTn) - realtime support / chat with the community and the team.
* [Discourse](https://discourse.linuxserver.io) - post on our community forum.
* [Fleet](https://fleet.linuxserver.io) - an online web interface which displays all of our maintained images.
* [GitHub](https://github.com/linuxserver) - view the source for all of our repositories.
* [Open Collective](https://opencollective.com/linuxserver) - please consider helping us by either donating or contributing to our budget

# [linuxserver/calibre](https://github.com/linuxserver/docker-calibre)

[![Scarf.io pulls](https://scarf.sh/installs-badge/linuxserver-ci/linuxserver%2Fcalibre?color=94398d&label-color=555555&logo-color=ffffff&style=for-the-badge&package-type=docker)](https://scarf.sh/gateway/linuxserver-ci/docker/linuxserver%2Fcalibre)
[![GitHub Stars](https://img.shields.io/github/stars/linuxserver/docker-calibre.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=github)](https://github.com/linuxserver/docker-calibre)
[![GitHub Release](https://img.shields.io/github/release/linuxserver/docker-calibre.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&logo=github)](https://github.com/linuxserver/docker-calibre/releases)
[![GitHub Package Repository](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitHub%20Package&logo=github)](https://github.com/linuxserver/docker-calibre/packages)
[![GitLab Container Registry](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=GitLab%20Registry&logo=gitlab)](https://gitlab.com/linuxserver.io/docker-calibre/container_registry)
[![Quay.io](https://img.shields.io/static/v1.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=linuxserver.io&message=Quay.io)](https://quay.io/repository/linuxserver.io/calibre)
[![Docker Pulls](https://img.shields.io/docker/pulls/linuxserver/calibre.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=pulls&logo=docker)](https://hub.docker.com/r/linuxserver/calibre)
[![Docker Stars](https://img.shields.io/docker/stars/linuxserver/calibre.svg?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=stars&logo=docker)](https://hub.docker.com/r/linuxserver/calibre)
[![Jenkins Build](https://img.shields.io/jenkins/build?labelColor=555555&logoColor=ffffff&style=for-the-badge&jobUrl=https%3A%2F%2Fci.linuxserver.io%2Fjob%2FDocker-Pipeline-Builders%2Fjob%2Fdocker-calibre%2Fjob%2Fmaster%2F&logo=jenkins)](https://ci.linuxserver.io/job/Docker-Pipeline-Builders/job/docker-calibre/job/master/)
[![LSIO CI](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=CI&query=CI&url=https%3A%2F%2Fci-tests.linuxserver.io%2Flinuxserver%2Fcalibre%2Flatest%2Fci-status.yml)](https://ci-tests.linuxserver.io/linuxserver/calibre/latest/index.html)

[Calibre](https://calibre-ebook.com/) is a powerful and easy to use e-book manager. Users say it's outstanding and a must-have. It'll allow you to do nearly everything and it takes things a step beyond normal e-book software. It's also completely free and open source and great for both casual users and computer experts.

[![calibre](https://github.com/kovidgoyal/calibre/raw/master/resources/images/lt.png)](https://calibre-ebook.com/)

## Supported Architectures

We utilise the docker manifest for multi-platform awareness. More information is available from docker [here](https://distribution.github.io/distribution/spec/manifest-v2-2/#manifest-list) and our announcement [here](https://blog.linuxserver.io/2019/02/21/the-lsio-pipeline-project/).

Simply pulling `lscr.io/linuxserver/calibre:latest` should retrieve the correct image for your arch, but you can also pull specific arch images via tags.

The architectures supported by this image are:

| Architecture | Available | Tag |
| :----: | :----: | ---- |
| x86-64 | ✅ | amd64-\<version tag\> |
| arm64 | ✅ | arm64v8-\<version tag\> |
| armhf | ❌ | |

## Application Setup

This image sets up the calibre desktop app and makes its interface available via Guacamole server in the browser. The interface is available at `http://your-ip:8080` or `https://your-ip:8181`.

By default, there is no password set for the main gui. Optional environment variable `PASSWORD` will allow setting a password for the user `abc`, via http auth.

Port 8081 is reserved for Calibre's built-in webserver, which can be enabled within the desktop app settings, and the internal port _must be_ set to `8081` although it will then be available at the host mapped port for external access.

### Options in all KasmVNC based GUI containers

This container is based on [Docker Baseimage KasmVNC](https://github.com/linuxserver/docker-baseimage-kasmvnc) which means there are additional environment variables and run configurations to enable or disable specific functionality.

#### Optional environment variables

| Variable | Description |
| :----: | --- |
| CUSTOM_PORT | Internal port the container listens on for http if it needs to be swapped from the default 8080. |
| CUSTOM_HTTPS_PORT | Internal port the container listens on for https if it needs to be swapped from the default 8181. |
| CUSTOM_USER | HTTP Basic auth username, abc is default. |
| PASSWORD | HTTP Basic auth password, abc is default. If unset there will be no auth |
| SUBFOLDER | Subfolder for the application if running a subfolder reverse proxy, need both slashes IE `/subfolder/` |
| TITLE | The page title displayed on the web browser, default "KasmVNC Client". |
| FM_HOME | This is the home directory (landing) for the file manager, default "/config". |
| START_DOCKER | If set to false a container with privilege will not automatically start the DinD Docker setup. |
| DRINODE | If mounting in /dev/dri for [DRI3 GPU Acceleration](https://www.kasmweb.com/kasmvnc/docs/master/gpu_acceleration.html) allows you to specify the device to use IE `/dev/dri/renderD128` |

#### Optional run configurations

| Variable | Description |
| :----: | --- |
| `--privileged` | Will start a Docker in Docker (DinD) setup inside the container to use docker in an isolated environment. For increased performance mount the Docker directory inside the container to the host IE `-v /home/user/docker-data:/var/lib/docker`. |
| `-v /var/run/docker.sock:/var/run/docker.sock` | Mount in the host level Docker socket to either interact with it via CLI or use Docker enabled applications. |
| `--device /dev/dri:/dev/dri` | Mount a GPU into the container, this can be used in conjunction with the `DRINODE` environment variable to leverage a host video card for GPU accelerated appplications. Only **Open Source** drivers are supported IE (Intel,AMDGPU,Radeon,ATI,Nouveau) |

### Lossless mode

This container is capable of delivering a true lossless image at a high framerate to your web browser by changing the Stream Quality preset to "Lossless", more information [here](https://www.kasmweb.com/docs/latest/how_to/lossless.html#technical-background). In order to use this mode from a non localhost endpoint the HTTPS port on 8181 needs to be used. If using a reverse proxy to port 8080 specific headers will need to be set as outlined [here](https://github.com/linuxserver/docker-baseimage-kasmvnc#lossless).

## Usage

To help you get started creating a container from this image you can either use docker-compose or the docker cli.

### docker-compose (recommended, [click here for more info](https://docs.linuxserver.io/general/docker-compose))

```yaml
---
services:
  calibre:
    image: lscr.io/linuxserver/calibre:latest
    container_name: calibre
    security_opt:
      - seccomp:unconfined #optional
    environment:
      - PUID=1000
      - PGID=1000
      - TZ=Etc/UTC
      - PASSWORD= #optional
      - CLI_ARGS= #optional
    volumes:
      - /path/to/data:/config
    ports:
      - 8080:8080
      - 8181:8181
      - 8081:8081
    restart: unless-stopped
```

### docker cli ([click here for more info](https://docs.docker.com/engine/reference/commandline/cli/))

```bash
docker run -d \
  --name=calibre \
  --security-opt seccomp=unconfined `#optional` \
  -e PUID=1000 \
  -e PGID=1000 \
  -e TZ=Etc/UTC \
  -e PASSWORD= `#optional` \
  -e CLI_ARGS= `#optional` \
  -p 8080:8080 \
  -p 8181:8181 \
  -p 8081:8081 \
  -v /path/to/data:/config \
  --restart unless-stopped \
  lscr.io/linuxserver/calibre:latest
```

## Parameters

Containers are configured using parameters passed at runtime (such as those above). These parameters are separated by a colon and indicate `<external>:<internal>` respectively. For example, `-p 8080:80` would expose port `80` from inside the container to be accessible from the host's IP on port `8080` outside the container.

| Parameter | Function |
| :----: | --- |
| `-p 8080` | Calibre desktop gui. |
| `-p 8181` | Calibre desktop gui HTTPS. |
| `-p 8081` | Calibre webserver gui. |
| `-e PUID=1000` | for UserID - see below for explanation |
| `-e PGID=1000` | for GroupID - see below for explanation |
| `-e TZ=Etc/UTC` | specify a timezone to use, see this [list](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones#List). |
| `-e PASSWORD=` | Optionally set a password for the gui. |
| `-e CLI_ARGS=` | Optionally pass cli start arguments to calibre. |
| `-v /config` | Where calibre should store its database and library. |
| `--security-opt seccomp=unconfined` | For Docker Engine only, many modern gui apps need this to function as syscalls are unkown to Docker. |

## Environment variables from files (Docker secrets)

You can set any environment variable from a file by using a special prepend `FILE__`.

As an example:

```bash
-e FILE__MYVAR=/run/secrets/mysecretvariable
```

Will set the environment variable `MYVAR` based on the contents of the `/run/secrets/mysecretvariable` file.

## Umask for running applications

For all of our images we provide the ability to override the default umask settings for services started within the containers using the optional `-e UMASK=022` setting.
Keep in mind umask is not chmod it subtracts from permissions based on it's value it does not add. Please read up [here](https://en.wikipedia.org/wiki/Umask) before asking for support.

## User / Group Identifiers

When using volumes (`-v` flags), permissions issues can arise between the host OS and the container, we avoid this issue by allowing you to specify the user `PUID` and group `PGID`.

Ensure any volume directories on the host are owned by the same user you specify and any permissions issues will vanish like magic.

In this instance `PUID=1000` and `PGID=1000`, to find yours use `id your_user` as below:

```bash
id your_user
```

Example output:

```text
uid=1000(your_user) gid=1000(your_user) groups=1000(your_user)
```

## Docker Mods

[![Docker Mods](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=calibre&query=%24.mods%5B%27calibre%27%5D.mod_count&url=https%3A%2F%2Fraw.githubusercontent.com%2Flinuxserver%2Fdocker-mods%2Fmaster%2Fmod-list.yml)](https://mods.linuxserver.io/?mod=calibre "view available mods for this container.") [![Docker Universal Mods](https://img.shields.io/badge/dynamic/yaml?color=94398d&labelColor=555555&logoColor=ffffff&style=for-the-badge&label=universal&query=%24.mods%5B%27universal%27%5D.mod_count&url=https%3A%2F%2Fraw.githubusercontent.com%2Flinuxserver%2Fdocker-mods%2Fmaster%2Fmod-list.yml)](https://mods.linuxserver.io/?mod=universal "view available universal mods.")

We publish various [Docker Mods](https://github.com/linuxserver/docker-mods) to enable additional functionality within the containers. The list of Mods available for this image (if any) as well as universal mods that can be applied to any one of our images can be accessed via the dynamic badges above.

## Support Info

* Shell access whilst the container is running:

    ```bash
    docker exec -it calibre /bin/bash
    ```

* To monitor the logs of the container in realtime:

    ```bash
    docker logs -f calibre
    ```

* Container version number:

    ```bash
    docker inspect -f '{{ index .Config.Labels "build_version" }}' calibre
    ```

* Image version number:

    ```bash
    docker inspect -f '{{ index .Config.Labels "build_version" }}' lscr.io/linuxserver/calibre:latest
    ```

## Updating Info

Most of our images are static, versioned, and require an image update and container recreation to update the app inside. With some exceptions (noted in the relevant readme.md), we do not recommend or support updating apps inside the container. Please consult the [Application Setup](#application-setup) section above to see if it is recommended for the image.

Below are the instructions for updating containers:

### Via Docker Compose

* Update images:
    * All images:

        ```bash
        docker-compose pull
        ```

    * Single image:

        ```bash
        docker-compose pull calibre
        ```

* Update containers:
    * All containers:

        ```bash
        docker-compose up -d
        ```

    * Single container:

        ```bash
        docker-compose up -d calibre
        ```

* You can also remove the old dangling images:

    ```bash
    docker image prune
    ```

### Via Docker Run

* Update the image:

    ```bash
    docker pull lscr.io/linuxserver/calibre:latest
    ```

* Stop the running container:

    ```bash
    docker stop calibre
    ```

* Delete the container:

    ```bash
    docker rm calibre
    ```

* Recreate a new container with the same docker run parameters as instructed above (if mapped correctly to a host folder, your `/config` folder and settings will be preserved)
* You can also remove the old dangling images:

    ```bash
    docker image prune
    ```

### Image Update Notifications - Diun (Docker Image Update Notifier)

**tip**: We recommend [Diun](https://crazymax.dev/diun/) for update notifications. Other tools that automatically update containers unattended are not recommended or supported.

## Building locally

If you want to make local modifications to these images for development purposes or just to customize the logic:

```bash
git clone https://github.com/linuxserver/docker-calibre.git
cd docker-calibre
docker build \
  --no-cache \
  --pull \
  -t lscr.io/linuxserver/calibre:latest .
```

The ARM variants can be built on x86_64 hardware using `multiarch/qemu-user-static`

```bash
docker run --rm --privileged multiarch/qemu-user-static:register --reset
```

Once registered you can define the dockerfile to use with `-f Dockerfile.aarch64`.

## Versions

* **17.11.23:** - Install libxcb-cursor0 for v7 support.
* **18.03.23:** - Rebase to KasmVNC base image.
* **19.10.22:** - Set the window title to `Calibre`. Remove websocat as it is now handled properly in the baseimage.
* **18.10.22:** - Deprecate Arch branch.
* **07.10.22:** - Start calibre window maximized.
* **16.09.22:** - Rebase to jammy.
* **24.07.22:** - Add arm64 build for master branch.
* **11.07.22:** - Update dependencies for Calibre 6.
* **28.05.22:** - Rebase to focal.
* **31.03.22:** - Fix umask.
* **28.02.22:** - Add speech support to bionic image.
* **05.01.22:** - Add arch branch for arm platforms.
* **20.04.21:** - Fix the HOME folder.
* **19.04.21:** - Add libnss3 back in. Make sure Calibre can access environment variables.
* **18.04.21:** - Start calibre on container start rather than gui connect.
* **15.04.21:** - Rebase to rdesktop-web baseimage. Deprecate `GUAC_USER` and `GUAC_PASS` env vars. Existing users can set the new var `PASSWORD` for the user `abc`.
* **25.09.20:** - Switch to python3, add various new dependencies for calibre 5.0.
* **10.05.19:** - Add new env var `CLI_ARGS` to pass start arguments to calibre.
* **18.03.19:** - Let Calibre access environment variables, add optional umask setting.
* **23.10.19:** - Remove reccomended deps and zenity for character compatibility.
* **18.10.19:** - Add python-xdg.
* **08.10.19:** - Add fonts-wqy-microhei ttf-wqy-zenhei fcitx-rime dependency to resolve issue with Chinese encoding.
* **04.10.19:** - Add libxkbcommon-x11-0 dependency to resolve issue with Calibre 4.
* **08.08.19:** - Add zenity for international character support in dialog boxes.
* **12.07.19:** - Download binary from calibre website instead of github.
* **29.04.19:** - Initial release.
