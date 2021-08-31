# Shodan

{% embed url="https://www.shodan.io" %}

## Basic filters

* **`city`**: find devices in a particular city
* **`country`**: find devices in a particular country
* **`geo`**: you can pass it coordinates
* **`hostname`**: find values that match the hostname
* **`net`**: search based on an IP or /x CIDR
* **`os`**: search based on operating system
* **`port`**: find particular ports that are open
* **`before/after`**: find results within a timeframe

## Examples

**Find Nginx servers in Finland**

```text
nginx country:”FI”
```

**Find with CVE-ID**

```text
vuln:cve-2014-0160
```

Find F5 Big-IP LB's on particular network

```text
BigIP net:“123.123.123.0/24”
```

