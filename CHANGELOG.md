## Netconf for ATOM

### 1.0.0 - Initial Release (27th June 2016)
* NETCONF client implementation using end-of-message framing
* Session authentication by username/password
* Establish/terminate NETCONF session (needed for transactions)
* Shortcuts for NETCONF transactions (lock, validate, discard, commit)
* Ability to compare running datastore against candidate
* Extensions to access Nokia SROS data models
* Embedded XML/XSLT/CSV tools
* NETCONF example library

Enhanced Features (beta):
* Receive NETCONF event notifications
* Smart XML TAG Selection using CTRL-SHIFT-A
* Generate CSV Table from XML using interactive XPATH

### 1.1.x - Updates (2016 November 9th)
* add support for base:1.1 chunked framing
* uprade to version 0.5 of ssh2 library
* add configurable rpc-request timeout (default 5min)
* improved cleanup for netconf errors/disconnect
* add support for SSH Greeting/Banner

### 1.2.0 - Example Library Updates (10. November 2016)
* New examples added for RFC6022, RFC7895
  (ietf-netconf-monitoring, yang library)
* Updated Nokia SROS examples for 14.0.R5 compatibility

### 1.3.x - Updates (2017 January 1st)
* New examples added for OpenConfig (BGP)
* Support for certificate based authentication
* Bugfix for timeout behavior
* Workaround for JUNOS interworking (multiple rpc-errors)
