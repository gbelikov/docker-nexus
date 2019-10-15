# docker-nexus
A container image for Sonatype Nexus Repository Manager OSS, based on Alpine Linux.

[![Docker Repository on Quay](https://quay.io/repository/travelaudience/docker-nexus/status "Docker Repository on Quay")](https://quay.io/repository/travelaudience/docker-nexus)

## Current software

* Alpine Linux 3.10
* OpenJDK JRE 8u212
* Nexus Repository Manager OSS 3.19.1 ([release notes](https://help.sonatype.com/repomanager3/release-notes/2019-release-notes#id-2019ReleaseNotes-RepositoryManager3.17.0))

# Build, tag, push
```
docker login
docker build --tag phansl/sonatype-nexus:3.19.1 --tag phansl/sonatype-nexus:latest .
docker push phansl/sonatype-nexus:3.19.1
docker push phansl/sonatype-nexus:latest
```
