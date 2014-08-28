# E3 Vagrant

## Installation

After cloning this repo, you will need to make a minor configuration change.

1. Look for the following line in your Vagrantfile. Edit it to reflect your projects directory.
```ruby
config.vm.synced_folder "~/development/docroot", "/vagrant_data", type: "nfs"
```
