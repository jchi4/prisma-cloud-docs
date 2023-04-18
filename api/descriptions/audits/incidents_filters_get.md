This endpoint lists the incident categories found in your environment.

The following example lists incident filters.

```bash
$ curl -k \
  -u <USER> \
  https://console:8083/api/vVERSION/audits/incidents/filters
```

Response:

```
{"hostname":["aqsa-lab.internal"],"category":["hijackedProcess","dataExfiltration"]}
```
