# Reconnaissance Query Inventory

This document provides a collection of passive reconnaissance search queries and examples that can be used during authorized security assessments to discover publicly indexed information and internet-facing assets. These examples are intended for educational purposes and for use only on systems you are authorized to assess.

## Google Search Queries (Google Dorks)

The following search patterns can help identify publicly available documents, login portals, and indexed resources.

### Locate Public PDF Documents

```text
site:mozilla.org filetype:pdf
```

### Discover Login Interfaces

```text
site:mozilla.org inurl:login
```

### Find Indexed Files

```text
site:blog.mozilla.org files
```

---

## Shodan Search Examples

The following Shodan queries can be used to identify publicly exposed services and internet-facing infrastructure.

### Search by Hostname

```text
hostname:mozilla.org
```

### Filter Nginx Services

```text
hostname:mozilla.org product:"nginx"
```

### Search for Services on Port 8443

```text
hostname:mozilla.org port:8443
```

---

## Notes

* These queries are examples for passive reconnaissance and asset discovery.
* Replace `mozilla.org` with the domain you are authorized to assess.
* Always perform security testing responsibly and only with proper authorization.
