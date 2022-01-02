## slack

[![CI](https://github.com/Oefenweb/ansible-slack/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-slack/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-slack-blue.svg)](https://galaxy.ansible.com/Oefenweb/slack)

Set up (the latest version of) [Slack](https://slack.com/downloads/linux) in Debian-like systems.

#### Requirements

None

#### Variables

* `slack_version` [default: `4.23.0`]: Version to install

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
