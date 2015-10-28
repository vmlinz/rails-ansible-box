# Rails Vagrant Box

Rails development box powered by ansible

Extracted from [railsbox](https://github.com/andreychernih/railsbox)

## Changes

* Use rsync to do one way sync from host to guest to get best file system performance and force to work outside of vagrant box

## Usage

* Same as rails box generated profile, copy the directory to rails app root
* Run `vagrant up` in development directory
