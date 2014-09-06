## ANXS - bootstraps [![Build Status](https://travis-ci.org/ANXS/bootstraps.png)](https://travis-ci.org/ANXS/bootstraps)

Ansible script which will run a set of bootstrap scripts for users


#### Requirements & Dependencies
- Tested on Ansible 1.4 or higher.


#### Variables

```yaml
bootstraps_commands:
  - user: foo
    command: "git clone --recursive https://github.com/pjan/ubuntu-dotfiles.git && cd ubuntu-dotfiles && set -- -f && source bootstrap.sh"
  - user: bar
    command: "cd /tmp && git clone --recursive https://github.com/pjan/vim-config.git && cd vim-config && set -- -f && source bootstrap.sh && sudo rm -r /tmp/vim-config"
```


#### License

Licensed under the MIT License. See the LICENSE file for details.


#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/ANXS/bootstraps/issues)!
