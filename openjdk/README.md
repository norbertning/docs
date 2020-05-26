<!--

********************************************************************************

WARNING:

    DO NOT EDIT "openjdk/README.md"

    IT IS AUTO-GENERATED

    (from the other files in "openjdk/" combined with a set of templates)

********************************************************************************

-->

**Note:** this is the "per-architecture" repository for the `arm64v8` builds of [the `openjdk` official image](https://hub.docker.com/_/openjdk) -- for more information, see ["Architectures other than amd64?" in the official images documentation](https://github.com/docker-library/official-images#architectures-other-than-amd64) and ["An image's source changed in Git, now what?" in the official images FAQ](https://github.com/docker-library/faq#an-images-source-changed-in-git-now-what).

# Quick reference

-	**Maintained by**:  
	[the Docker Community](https://github.com/docker-library/openjdk)

-	**Where to get help**:  
	[the Docker Community Forums](https://forums.docker.com/), [the Docker Community Slack](http://dockr.ly/slack), or [Stack Overflow](https://stackoverflow.com/search?tab=newest&q=docker)

# Supported tags and respective `Dockerfile` links

(See ["What's the difference between 'Shared' and 'Simple' tags?" in the FAQ](https://github.com/docker-library/faq#whats-the-difference-between-shared-and-simple-tags).)

## Simple Tags

-	[`15-ea-24-jdk-oraclelinux7`, `15-ea-24-oraclelinux7`, `15-ea-jdk-oraclelinux7`, `15-ea-oraclelinux7`, `15-jdk-oraclelinux7`, `15-oraclelinux7`, `15-ea-24-jdk-oracle`, `15-ea-24-oracle`, `15-ea-jdk-oracle`, `15-ea-oracle`, `15-jdk-oracle`, `15-oracle`](https://github.com/docker-library/openjdk/blob/bb4265f075850b8b6b36347d0cb045a3fa4df18e/15/jdk/oracle/Dockerfile)
-	[`15-ea-24-jdk-buster`, `15-ea-24-buster`, `15-ea-jdk-buster`, `15-ea-buster`, `15-jdk-buster`, `15-buster`](https://github.com/docker-library/openjdk/blob/bb4265f075850b8b6b36347d0cb045a3fa4df18e/15/jdk/Dockerfile)
-	[`15-ea-24-jdk-slim-buster`, `15-ea-24-slim-buster`, `15-ea-jdk-slim-buster`, `15-ea-slim-buster`, `15-jdk-slim-buster`, `15-slim-buster`, `15-ea-24-jdk-slim`, `15-ea-24-slim`, `15-ea-jdk-slim`, `15-ea-slim`, `15-jdk-slim`, `15-slim`](https://github.com/docker-library/openjdk/blob/bb4265f075850b8b6b36347d0cb045a3fa4df18e/15/jdk/slim/Dockerfile)
-	[`11.0.7-jdk-buster`, `11.0.7-buster`, `11.0-jdk-buster`, `11.0-buster`, `11-jdk-buster`, `11-buster`](https://github.com/docker-library/openjdk/blob/bce2fa373dc270cccf539a8e31b5f2a432d23738/11/jdk/Dockerfile)
-	[`11.0.7-jdk-slim-buster`, `11.0.7-slim-buster`, `11.0-jdk-slim-buster`, `11.0-slim-buster`, `11-jdk-slim-buster`, `11-slim-buster`, `11.0.7-jdk-slim`, `11.0.7-slim`, `11.0-jdk-slim`, `11.0-slim`, `11-jdk-slim`, `11-slim`](https://github.com/docker-library/openjdk/blob/bce2fa373dc270cccf539a8e31b5f2a432d23738/11/jdk/slim/Dockerfile)
-	[`11.0.7-jre-buster`, `11.0-jre-buster`, `11-jre-buster`](https://github.com/docker-library/openjdk/blob/bce2fa373dc270cccf539a8e31b5f2a432d23738/11/jre/Dockerfile)
-	[`11.0.7-jre-slim-buster`, `11.0-jre-slim-buster`, `11-jre-slim-buster`, `11.0.7-jre-slim`, `11.0-jre-slim`, `11-jre-slim`](https://github.com/docker-library/openjdk/blob/bce2fa373dc270cccf539a8e31b5f2a432d23738/11/jre/slim/Dockerfile)

## Shared Tags

-	`15-ea-24-jdk`, `15-ea-24`, `15-ea-jdk`, `15-ea`, `15-jdk`, `15`:
	-	[`15-ea-24-jdk-oraclelinux7`](https://github.com/docker-library/openjdk/blob/bb4265f075850b8b6b36347d0cb045a3fa4df18e/15/jdk/oracle/Dockerfile)
-	`11.0.7-jdk`, `11.0.7`, `11.0-jdk`, `11.0`, `11-jdk`, `11`:
	-	[`11.0.7-jdk-buster`](https://github.com/docker-library/openjdk/blob/bce2fa373dc270cccf539a8e31b5f2a432d23738/11/jdk/Dockerfile)
-	`11.0.7-jre`, `11.0-jre`, `11-jre`:
	-	[`11.0.7-jre-buster`](https://github.com/docker-library/openjdk/blob/bce2fa373dc270cccf539a8e31b5f2a432d23738/11/jre/Dockerfile)

[![arm64v8/openjdk build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/arm64v8/job/openjdk.svg?label=arm64v8/openjdk%20%20build%20job)](https://doi-janky.infosiftr.net/job/multiarch/job/arm64v8/job/openjdk/)

# Quick reference (cont.)

-	**Where to file issues**:  
	[https://github.com/docker-library/openjdk/issues](https://github.com/docker-library/openjdk/issues)

-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))  
	[`amd64`](https://hub.docker.com/r/amd64/openjdk/), [`arm64v8`](https://hub.docker.com/r/arm64v8/openjdk/), [`windows-amd64`](https://hub.docker.com/r/winamd64/openjdk/)

-	**Published image artifact details**:  
	[repo-info repo's `repos/openjdk/` directory](https://github.com/docker-library/repo-info/blob/master/repos/openjdk) ([history](https://github.com/docker-library/repo-info/commits/master/repos/openjdk))  
	(image metadata, transfer size, etc)

-	**Image updates**:  
	[official-images PRs with label `library/openjdk`](https://github.com/docker-library/official-images/pulls?q=label%3Alibrary%2Fopenjdk)  
	[official-images repo's `library/openjdk` file](https://github.com/docker-library/official-images/blob/master/library/openjdk) ([history](https://github.com/docker-library/official-images/commits/master/library/openjdk))

-	**Source of this description**:  
	[docs repo's `openjdk/` directory](https://github.com/docker-library/docs/tree/master/openjdk) ([history](https://github.com/docker-library/docs/commits/master/openjdk))

# What is OpenJDK?

OpenJDK (Open Java Development Kit) is a free and open source implementation of the Java Platform, Standard Edition (Java SE). OpenJDK is the official reference implementation of Java SE since version 7.

> [wikipedia.org/wiki/OpenJDK](http://en.wikipedia.org/wiki/OpenJDK)

Java is a registered trademark of Oracle and/or its affiliates.

![logo](https://raw.githubusercontent.com/docker-library/docs/a3439b66b7980d1811f6b3835a3c541747172970/openjdk/logo.png)

# How to use this image

## Start a Java instance in your app

The most straightforward way to use this image is to use a Java container as both the build and runtime environment. In your `Dockerfile`, writing something along the lines of the following will compile and run your project:

```dockerfile
FROM arm64v8/openjdk:7
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN javac Main.java
CMD ["java", "Main"]
```

You can then run and build the Docker image:

```console
$ docker build -t my-java-app .
$ docker run -it --rm --name my-running-app my-java-app
```

## Compile your app inside the Docker container

There may be occasions where it is not appropriate to run your app inside a container. To compile, but not run your app inside the Docker instance, you can write something like:

```console
$ docker run --rm -v "$PWD":/usr/src/myapp -w /usr/src/myapp arm64v8/openjdk:7 javac Main.java
```

This will add your current directory as a volume to the container, set the working directory to the volume, and run the command `javac Main.java` which will tell Java to compile the code in `Main.java` and output the Java class file to `Main.class`.

## Make JVM respect CPU and RAM limits

On startup the JVM tries to detect the number of available CPU cores and RAM to adjust its internal parameters (like the number of garbage collector threads to spawn) accordingly. When the container is ran with limited CPU/RAM then the standard system API used by the JVM for probing it will return host-wide values. This can cause excessive CPU usage and memory allocation errors with older versions of the JVM.

Inside Linux containers, OpenJDK versions 8 and later can correctly detect the container-limited number of CPU cores and available RAM. For all currently supported OpenJDK versions this is turned on by default.

Inside Windows Server (non-Hyper-V) containers, the limit for the number of available CPU cores doesn't work (it's ignored by Host Compute Service). To set the limit manually the JVM can be started as:

```console
$ start /b /wait /affinity 0x3 path/to/java.exe ...
```

In this example CPU affinity hex mask `0x3` will limit the JVM to 2 CPU cores.

RAM limit is supported by Windows Server containers, but currently the JVM cannot detect it. To prevent excessive memory allocations, `-XX:MaxRAM=...` option must be specified with the value that is not bigger than the containers RAM limit.

## Environment variables with periods in their names

Some shells (notably, [the BusyBox `/bin/sh` included in Alpine Linux](https://github.com/docker-library/openjdk/issues/135)) do not support environment variables with periods in the names (which are technically not POSIX compliant), and thus *strip* them instead of passing them through (as Bash does). If your application requires environment variables of this form, either use `CMD ["java", ...]` directly (no shell), or (install and) use Bash explicitly instead of `/bin/sh`.

# Image Variants

The `arm64v8/openjdk` images come in many flavors, each designed for a specific use case.

## `arm64v8/openjdk:<version>`

This is the defacto image. If you are unsure about what your needs are, you probably want to use this one. It is designed to be used both as a throw away container (mount your source code and start the container to start your app), as well as the base to build other images off of.

Some of these tags may have names like buster in them. These are the suite code names for releases of [Debian](https://wiki.debian.org/DebianReleases) and indicate which release the image is based on. If your image needs to install any additional packages beyond what comes with the image, you'll likely want to specify one of these explicitly to minimize breakage when there are new releases of Debian.

## `arm64v8/openjdk:<version>` (from 12 onwards), `arm64v8/openjdk:<version>-oracle` and `arm64v8/openjdk:<version>-oraclelinux7`

Starting with `openjdk:12` the default image as well as the `-oracle` and `-oraclelinux7` variants are based on the official [Oracle Linux 7 image](https://hub.docker.com/_/oraclelinux) which is provided under the GPLv2 as per the [Oracle Linux End User Agreement (EULA)](https://oss.oracle.com/ol7/EULA).

The OpenJDK binaries in the default image as well as the `-oracle` and `-oraclelinux7` variants are built by Oracle and are sourced from the [OpenJDK community](https://openjdk.java.net/). These binaries are licensed under the [GPLv2 with the Classpath Exception](https://openjdk.java.net/legal/gplv2+ce.html).

# License

View [license information](http://openjdk.java.net/legal/gplv2+ce.html) for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `openjdk/` directory](https://github.com/docker-library/repo-info/tree/master/repos/openjdk).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
