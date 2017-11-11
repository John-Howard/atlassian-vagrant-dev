# Vagrant Development Environment for Atlassina Plugin Development

Use this vagrant file and ansible playbook to bootstrap your atlassian plugin development environment.

## How to Use

### Pre-requisite

You have to have Vagrant and VirtualBox already installed on your computer.

### Creating the VM
1. Git clone / or copy the files.
2. ```sh vagrant up```
3. Get a cup of coffe and wait.

## Common Issues

### Error when installing the atlassian sdk

It might happen that the atlassian sdk installatin fails when you're doing it over WiFi network. If your network slows down, some packages might be wrong and the TLS will not like.

Solution: Try again when your internet connection get better.
```sh vagrant up --provision``` 
