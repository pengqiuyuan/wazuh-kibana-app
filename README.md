# Wazuh - Kibana App

## Requisites

- Wazuh HIDS 2.0 or superior
- Wazuh RESTful API 2.0 or superior
- Kibana 5.2.2 or superior
- Elasticsearch 5 or superior

## Installation

| Kibana version | Installation |
| :---:         |     :---      |
| 5.2.2  | /usr/share/kibana/bin/kibana-plugin install https://packages.wazuh.com/wazuhapp/wazuhapp-2.0_5.2.2.zip  |
| 5.3.0  | /usr/share/kibana/bin/kibana-plugin install https://packages.wazuh.com/wazuhapp/wazuhapp-2.0_5.3.0.zip  |
| 5.3.1  | /usr/share/kibana/bin/kibana-plugin install https://packages.wazuh.com/wazuhapp/wazuhapp-2.0_5.3.1.zip  |
| 5.4.0  | /usr/share/kibana/bin/kibana-plugin install https://packages.wazuh.com/wazuhapp/wazuhapp-2.0_5.4.0.zip  |
## Upgrade

Remove the App using kibana-plugin tool

```/usr/share/kibana/bin/kibana-plugin remove wazuh ```

Install the App

```/usr/share/kibana/bin/kibana-plugin install https://packages.wazuh.com/wazuhapp/wazuhapp-2.0_5.x.x.zip ```


## Documentation

* [Full documentation](https://documentation.wazuh.com)
* [Wazuh installation guide](https://documentation.wazuh.com/current/installation-guide/index.html)
* [Screenshots](https://documentation.wazuh.com/current/index.html#example-screenshots)

## Branches

* `stable` branch on correspond to the last stable version.
* `master` branch contains the latest code, be aware of possible bugs on this branch.
* `development` branch includes all the new features we're adding and testing.

## Contribute

If you want to contribute to our project please don't hesitate to send a pull request. You can also join our users [mailing list](https://groups.google.com/d/forum/wazuh), by sending an email to [wazuh+subscribe@googlegroups.com](mailto:wazuh+subscribe@googlegroups.com), to ask questions and participate in discussions.

## Software and libraries used

* API from Elastic and Kibana (elastic.co).
* Angular Material (material.angularjs.org).
* Bootstrap (getbootstrap.com).
* AngularJS.
* Node.js (Ryan Dahl).
* NPM packages Angular animate, aria, cookies, md5, needle and cron.

## License and copyright

Wazuh App Copyright (C) 2016 Wazuh Inc. (License GPLv2)

## References

* [Wazuh website](https://wazuh.com)
* [Wazuh documentation](https://documentation.wazuh.com)
* [Elastic stack](https://elastic.co)
