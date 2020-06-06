# Conan Config

A general Conan configuration for CCDC packages

### Introduction

[Conan config](https://docs.conan.io/en/latest/reference/commands/consumer/config.html) provides the option to distribute and share remotes, profiles, settings.

[[Webinar] Developing C/C++ packages with Conan: new features](https://youtu.be/Aey_O86mSfg)

### install

To apply this template in your current environment:

    $ conan config install https://ccdc@dev.azure.com/ccdc/ccdc-3rd-party/_git/conan-3rd-party-configuration

or

    $ conan config install git@ssh.dev.azure.com:v3/ccdc/ccdc-3rd-party/conan-3rd-party-configuration

Git branches can be installed with

    $ conan config install git@ssh.dev.azure.com:v3/ccdc/ccdc-3rd-party/conan-3rd-party-configuration --args "-b tag"