# POSH-Kubernetes

POSH-Kubernetes

Curent state of this module is experimental

# Git

Clone this repository

    git clone https://github.com/loanDepot/POSH-Kubernetes.git

# Building

Run the build script in the root of the project to install dependent modules and start the build

    .\build.ps1

To just run the build, execute Invoke-Build

    Invoke-Build

    # or do a clean build
    Invoke-Build Clean,Default


Install dev version of the module on the local system after building it.

    Invoke-Build Install
