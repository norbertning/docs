<!--

********************************************************************************

WARNING:

    DO NOT EDIT "adoptopenjdk/README.md"

    IT IS AUTO-GENERATED

    (from the other files in "adoptopenjdk/" combined with a set of templates)

********************************************************************************

-->

**Note:** this is the "per-architecture" repository for the `s390x` builds of [the `adoptopenjdk` official image](https://hub.docker.com/_/adoptopenjdk) -- for more information, see ["Architectures other than amd64?" in the official images documentation](https://github.com/docker-library/official-images#architectures-other-than-amd64) and ["An image's source changed in Git, now what?" in the official images FAQ](https://github.com/docker-library/faq#an-images-source-changed-in-git-now-what).

# Quick reference

-	**Maintained by**:  
	[AdoptOpenJDK](https://github.com/AdoptOpenJDK/openjdk-docker)

-	**Where to get help**:  
	[AdoptOpenJDK Slack](https://adoptopenjdk.net/slack.html); [AdoptOpenJDK Mailing List](https://mail.openjdk.java.net/mailman/listinfo/adoption-discuss); [Eclipse OpenJ9 Slack](https://www.eclipse.org/openj9/oj9_joinslack.html); [Eclipse OpenJ9 Mailing List](https://dev.eclipse.org/mailman/listinfo/openj9-dev)

# Supported tags and respective `Dockerfile` links

(See ["What's the difference between 'Shared' and 'Simple' tags?" in the FAQ](https://github.com/docker-library/faq#whats-the-difference-between-shared-and-simple-tags).)

## Simple Tags

-	[`8u252-b09-jdk-hotspot-bionic`, `8-jdk-hotspot-bionic`, `8-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/8/jdk/ubuntu/Dockerfile.hotspot.releases.full)
-	[`8u252-b09-jre-hotspot-bionic`, `8-jre-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/8/jre/ubuntu/Dockerfile.hotspot.releases.full)
-	[`11.0.7_10-jdk-hotspot-bionic`, `11-jdk-hotspot-bionic`, `11-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/11/jdk/ubuntu/Dockerfile.hotspot.releases.full)
-	[`11.0.7_10-jre-hotspot-bionic`, `11-jre-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/11/jre/ubuntu/Dockerfile.hotspot.releases.full)
-	[`13.0.2_8-jdk-hotspot-bionic`, `13-jdk-hotspot-bionic`, `13-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/3b28dd3fb7230f208ed49da507432a01741b1259/13/jdk/ubuntu/Dockerfile.hotspot.releases.full)
-	[`13.0.2_8-jre-hotspot-bionic`, `13-jre-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/3b28dd3fb7230f208ed49da507432a01741b1259/13/jre/ubuntu/Dockerfile.hotspot.releases.full)
-	[`14.0.1_7-jdk-hotspot-bionic`, `14-jdk-hotspot-bionic`, `14-hotspot-bionic`, `hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/2fb3fcc43ea049fd4bd020910e23ecdf492deb58/14/jdk/ubuntu/Dockerfile.hotspot.releases.full)
-	[`14.0.1_7-jre-hotspot-bionic`, `14-jre-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/2fb3fcc43ea049fd4bd020910e23ecdf492deb58/14/jre/ubuntu/Dockerfile.hotspot.releases.full)
-	[`8u252-b09-jdk-openj9-0.20.0-bionic`, `8-jdk-openj9-bionic`, `8-openj9-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/8/jdk/ubuntu/Dockerfile.openj9.releases.full)
-	[`8u252-b09-jre-openj9-0.20.0-bionic`, `8-jre-openj9-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/8/jre/ubuntu/Dockerfile.openj9.releases.full)
-	[`11.0.7_10-jdk-openj9-0.20.0-bionic`, `11-jdk-openj9-bionic`, `11-openj9-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/11/jdk/ubuntu/Dockerfile.openj9.releases.full)
-	[`11.0.7_10-jre-openj9-0.20.0-bionic`, `11-jre-openj9-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/11/jre/ubuntu/Dockerfile.openj9.releases.full)
-	[`13.0.2_8-jdk-openj9-0.18.0-bionic`, `13-jdk-openj9-bionic`, `13-openj9-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/3b28dd3fb7230f208ed49da507432a01741b1259/13/jdk/ubuntu/Dockerfile.openj9.releases.full)
-	[`13.0.2_8-jre-openj9-0.18.0-bionic`, `13-jre-openj9-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/3b28dd3fb7230f208ed49da507432a01741b1259/13/jre/ubuntu/Dockerfile.openj9.releases.full)
-	[`14.0.1_7-jdk-openj9-0.20.0-bionic`, `14-jdk-openj9-bionic`, `14-openj9-bionic`, `openj9-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/14/jdk/ubuntu/Dockerfile.openj9.releases.full)
-	[`14.0.1_7-jre-openj9-0.20.0-bionic`, `14-jre-openj9-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/14/jre/ubuntu/Dockerfile.openj9.releases.full)

## Shared Tags

-	`8u252-b09-jdk-hotspot`:
	-	[`8u252-b09-jdk-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/8/jdk/ubuntu/Dockerfile.hotspot.releases.full)
-	`8-jdk-hotspot`, `8-hotspot`:
	-	[`8u252-b09-jdk-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/8/jdk/ubuntu/Dockerfile.hotspot.releases.full)
-	`8u252-b09-jre-hotspot`:
	-	[`8u252-b09-jre-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/8/jre/ubuntu/Dockerfile.hotspot.releases.full)
-	`8-jre-hotspot`:
	-	[`8u252-b09-jre-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/8/jre/ubuntu/Dockerfile.hotspot.releases.full)
-	`11.0.7_10-jdk-hotspot`:
	-	[`11.0.7_10-jdk-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/11/jdk/ubuntu/Dockerfile.hotspot.releases.full)
-	`11-jdk-hotspot`, `11-hotspot`:
	-	[`11.0.7_10-jdk-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/11/jdk/ubuntu/Dockerfile.hotspot.releases.full)
-	`11.0.7_10-jre-hotspot`:
	-	[`11.0.7_10-jre-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/11/jre/ubuntu/Dockerfile.hotspot.releases.full)
-	`11-jre-hotspot`:
	-	[`11.0.7_10-jre-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/11/jre/ubuntu/Dockerfile.hotspot.releases.full)
-	`13.0.2_8-jdk-hotspot`, `13-jdk-hotspot`, `13-hotspot`:
	-	[`13.0.2_8-jdk-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/3b28dd3fb7230f208ed49da507432a01741b1259/13/jdk/ubuntu/Dockerfile.hotspot.releases.full)
-	`13.0.2_8-jre-hotspot`, `13-jre-hotspot`:
	-	[`13.0.2_8-jre-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/3b28dd3fb7230f208ed49da507432a01741b1259/13/jre/ubuntu/Dockerfile.hotspot.releases.full)
-	`14.0.1_7-jdk-hotspot`:
	-	[`14.0.1_7-jdk-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/2fb3fcc43ea049fd4bd020910e23ecdf492deb58/14/jdk/ubuntu/Dockerfile.hotspot.releases.full)
-	`14-jdk-hotspot`, `14-hotspot`, `hotspot`, `latest`:
	-	[`14.0.1_7-jdk-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/2fb3fcc43ea049fd4bd020910e23ecdf492deb58/14/jdk/ubuntu/Dockerfile.hotspot.releases.full)
-	`14.0.1_7-jre-hotspot`:
	-	[`14.0.1_7-jre-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/2fb3fcc43ea049fd4bd020910e23ecdf492deb58/14/jre/ubuntu/Dockerfile.hotspot.releases.full)
-	`14-jre-hotspot`:
	-	[`14.0.1_7-jre-hotspot-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/2fb3fcc43ea049fd4bd020910e23ecdf492deb58/14/jre/ubuntu/Dockerfile.hotspot.releases.full)
-	`8u252-b09-jdk-openj9-0.20.0`:
	-	[`8u252-b09-jdk-openj9-0.20.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/8/jdk/ubuntu/Dockerfile.openj9.releases.full)
-	`8-jdk-openj9`, `8-openj9`:
	-	[`8u252-b09-jdk-openj9-0.20.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/8/jdk/ubuntu/Dockerfile.openj9.releases.full)
-	`8u252-b09-jre-openj9-0.20.0`:
	-	[`8u252-b09-jre-openj9-0.20.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/8/jre/ubuntu/Dockerfile.openj9.releases.full)
-	`8-jre-openj9`:
	-	[`8u252-b09-jre-openj9-0.20.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/8/jre/ubuntu/Dockerfile.openj9.releases.full)
-	`11.0.7_10-jdk-openj9-0.20.0`:
	-	[`11.0.7_10-jdk-openj9-0.20.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/11/jdk/ubuntu/Dockerfile.openj9.releases.full)
-	`11-jdk-openj9`, `11-openj9`:
	-	[`11.0.7_10-jdk-openj9-0.20.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/11/jdk/ubuntu/Dockerfile.openj9.releases.full)
-	`11.0.7_10-jre-openj9-0.20.0`:
	-	[`11.0.7_10-jre-openj9-0.20.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/11/jre/ubuntu/Dockerfile.openj9.releases.full)
-	`11-jre-openj9`:
	-	[`11.0.7_10-jre-openj9-0.20.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/11/jre/ubuntu/Dockerfile.openj9.releases.full)
-	`13.0.2_8-jdk-openj9-0.18.0`, `13-jdk-openj9`, `13-openj9`:
	-	[`13.0.2_8-jdk-openj9-0.18.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/3b28dd3fb7230f208ed49da507432a01741b1259/13/jdk/ubuntu/Dockerfile.openj9.releases.full)
-	`13.0.2_8-jre-openj9-0.18.0`, `13-jre-openj9`:
	-	[`13.0.2_8-jre-openj9-0.18.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/3b28dd3fb7230f208ed49da507432a01741b1259/13/jre/ubuntu/Dockerfile.openj9.releases.full)
-	`14.0.1_7-jdk-openj9-0.20.0`:
	-	[`14.0.1_7-jdk-openj9-0.20.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/14/jdk/ubuntu/Dockerfile.openj9.releases.full)
-	`14-jdk-openj9`, `14-openj9`, `openj9`:
	-	[`14.0.1_7-jdk-openj9-0.20.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/14/jdk/ubuntu/Dockerfile.openj9.releases.full)
-	`14.0.1_7-jre-openj9-0.20.0`:
	-	[`14.0.1_7-jre-openj9-0.20.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/14/jre/ubuntu/Dockerfile.openj9.releases.full)
-	`14-jre-openj9`:
	-	[`14.0.1_7-jre-openj9-0.20.0-bionic`](https://github.com/AdoptOpenJDK/openjdk-docker/blob/f104ef0fd80dc1d8e2b796a80f00512ab06a1465/14/jre/ubuntu/Dockerfile.openj9.releases.full)

[![s390x/adoptopenjdk build status badge](https://img.shields.io/jenkins/s/https/doi-janky.infosiftr.net/job/multiarch/job/s390x/job/adoptopenjdk.svg?label=s390x/adoptopenjdk%20%20build%20job)](https://doi-janky.infosiftr.net/job/multiarch/job/s390x/job/adoptopenjdk/)

# Quick reference (cont.)

-	**Where to file issues**:  
	[GitHub](https://github.com/AdoptOpenJDK/openjdk-docker/issues); The [adoptopenjdk support](https://adoptopenjdk.net/support.html) page has more information on quality, roadmap and support levels for AdoptOpenJDK builds;

-	**Supported architectures**: ([more info](https://github.com/docker-library/official-images#architectures-other-than-amd64))  
	[`amd64`](https://hub.docker.com/r/amd64/adoptopenjdk/), [`arm32v7`](https://hub.docker.com/r/arm32v7/adoptopenjdk/), [`arm64v8`](https://hub.docker.com/r/arm64v8/adoptopenjdk/), [`ppc64le`](https://hub.docker.com/r/ppc64le/adoptopenjdk/), [`s390x`](https://hub.docker.com/r/s390x/adoptopenjdk/), [`windows-amd64`](https://hub.docker.com/r/winamd64/adoptopenjdk/)

-	**Published image artifact details**:  
	[repo-info repo's `repos/adoptopenjdk/` directory](https://github.com/docker-library/repo-info/blob/master/repos/adoptopenjdk) ([history](https://github.com/docker-library/repo-info/commits/master/repos/adoptopenjdk))  
	(image metadata, transfer size, etc)

-	**Image updates**:  
	[official-images PRs with label `library/adoptopenjdk`](https://github.com/docker-library/official-images/pulls?q=label%3Alibrary%2Fadoptopenjdk)  
	[official-images repo's `library/adoptopenjdk` file](https://github.com/docker-library/official-images/blob/master/library/adoptopenjdk) ([history](https://github.com/docker-library/official-images/commits/master/library/adoptopenjdk))

-	**Source of this description**:  
	[docs repo's `adoptopenjdk/` directory](https://github.com/docker-library/docs/tree/master/adoptopenjdk) ([history](https://github.com/docker-library/docs/commits/master/adoptopenjdk))

## Overview

The images in this repository contain OpenJDK binaries that are built by AdoptOpenJDK and contain both HotSpot and Eclipse OpenJ9 JVMs.

# What is AdoptOpenJDK ?

[AdoptOpenJDK](https://adoptopenjdk.net/) is a community of Java™ user group members, Java developers and vendors who are advocates of OpenJDK, the open source project which forms the basis of the Java programming language and platform. AdoptOpenJDK provides prebuilt OpenJDK binaries from a fully open source set of build scripts and infrastructure. AdoptOpenJDK builds and tests binaries for different source code streams based upon OpenJDK. Our binaries undergo extensive testing, and the Releases have passed all the available OpenJDK test suites and our additional tests (donated by the community), ensuring the best quality binary available.

Java and all Java-based trademarks and logos are trademarks or registered trademarks of Oracle and/or its affiliates.

![logo](https://raw.githubusercontent.com/docker-library/docs/0db0af87e256d941bf011e3b5b06ca4a8edb6b84/adoptopenjdk/logo.png)

# What is Eclipse OpenJ9 ?

[Eclipse OpenJ9](https://www.eclipse.org/openj9/) is a high performance, scalable, Java virtual machine (JVM) implementation that has a proven track record of running Java applications in production environments. Contributed to the Eclipse project by IBM, the OpenJ9 JVM underpins the IBM SDK, Java Technology Edition product that is a core component of many IBM Enterprise software products. Continued development of OpenJ9 at the Eclipse foundation ensures wider collaboration, fresh innovation, and the opportunity to influence the development of OpenJ9 for the next generation of Java applications. OpenJDK binaries that include Eclipse OpenJ9 are available through AdoptOpenJDK.

# Images

There are two types of Docker images here: the Java Development Kit (JDK) and the Java Runtime Environment (JRE). These images can be used as the basis for custom built images for running your applications.

### Multi-Arch Image

Docker Images for the following architectures are now available:

-	HotSpot
	-	`amd64`, `arm32v7`, `arm64v8`, `ppc64le`, `s390x`, `windows-amd64`
-	Eclipse OpenJ9
	-	`amd64`, `ppc64le`, `s390x`, `windows-amd64`

# How to use this Image

To run a pre-built jar file with the latest OpenJDK 11 with HotSpot JRE image, use the following Dockerfile:

```dockerfile
FROM s390x/adoptopenjdk:11-jre-hotspot
RUN mkdir /opt/app
COPY japp.jar /opt/app
CMD ["java", "-jar", "/opt/app/japp.jar"]
```

To do the same with the latest OpenJDK 11 with Eclipse OpenJ9 JRE image, use the following Dockerfile:

```dockerfile
FROM s390x/adoptopenjdk:11-jre-openj9
RUN mkdir /opt/app
COPY japp.jar /opt/app
CMD ["java", "-jar", "/opt/app/japp.jar"]
```

You can build and run the Docker Image as shown in the following example:

```console
docker build -t japp .
docker run -it --rm japp
```

If you want to place the jar file on the host file system instead of inside the container, you can mount the host path onto the container by using the following commands:

```dockerfile
FROM s390x/adoptopenjdk:12.0.1_12-jdk-openj9-0.14.1
CMD ["java", "-jar", "/opt/app/japp.jar"]
```

```console
docker build -t japp .
docker run -it -v /path/on/host/system/jars:/opt/app japp
```

# License

The Dockerfiles and associated scripts are licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).

Licenses for the products installed within the images:

-	Eclipse OpenJ9 + OpenJDK: The combined works license is [GNU GPL v2 with Classpath Exception](http://openjdk.java.net/legal/gplv2+ce.html).
-	OpenJDK: The project license is GNU GPL v2 with Classpath Exception.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in [the `repo-info` repository's `adoptopenjdk/` directory](https://github.com/docker-library/repo-info/tree/master/repos/adoptopenjdk).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
