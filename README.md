## Ansibles - bootstraps [![Build Status](https://travis-ci.org/Ansibles/bootstraps.png)](https://travis-ci.org/Ansibles/bootstraps)

Ansible script which will run a set of bootstrap scripts for users


#### Requirements & Dependencies
- Tested on Ansible 1.4 or higher.


#### Variables

```yaml
bootstraps_commands:
  - user: pjan
    command: "git clone --recursive https://github.com/pjan/ubuntu-dotfiles.git && cd ubuntu-dotfiles && set -- -f && source bootstrap.sh"
```


#### License

Licensed under the MIT License. See the LICENSE file for details.


#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/ansibles/bootstraps/issues)!
