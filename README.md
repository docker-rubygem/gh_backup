[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/gh_backup.svg)](https://hub.docker.com/r/rubygem/gh_backup/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/gh_backup.svg)](https://hub.docker.com/r/rubygem/gh_backup/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/gh_backup.svg)](https://hub.docker.com/r/rubygem/gh_backup/)
[![Gem Downloads](https://img.shields.io/gem/dt/gh_backup.svg)](https://rubygems.org/gems/gh_backup/)
# gh_backup

Auto-Generated Docker image for gh_backup to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/gh_backup`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/gh_backup`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/gh_backup`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/gh_backup/)
