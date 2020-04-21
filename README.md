## slack

[![Build Status](https://travis-ci.org/Oefenweb/ansible-slack.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-slack)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-slack-blue.svg)](https://galaxy.ansible.com/Oefenweb/slack)

Set up (the latest version of) [Slack](https://slack.com/downloads/linux) in Debian-like systems.

#### Requirements

None

#### Variables

* `slack_version` [default: `4.4.2`]: Version to install

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - slack
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-slack/issues)!
