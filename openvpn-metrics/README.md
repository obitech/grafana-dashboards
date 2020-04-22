# OpenVPN Metrics

Extends louish's OpenVPN Dashboard (ID: 10562) with instance
labels and some fixes.

Also uses IP addresses instead of user names to be compliant with
data protection guidelines that might be present in certain
organizations (label `virtual_address` instead of `common_name`).

Requires [openvpn_exporter](https://github.com/kumina/openvpn_exporter).