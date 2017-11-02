# ansible-role-roseguarden
ansible role to setup roseguarden

This is work in progress and does not work quite well yet. There are a lot of
hacks. The setup process used here differs in many ways from the official
guide. For example it tries to install most dependencies using Debian
packages provided in the offical Debian APT repository and uses a Docker
build container to compile the client interface instead of installing
nodejs on the target device.
