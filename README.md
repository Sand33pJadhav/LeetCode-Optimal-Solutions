# LeetCode-Optimal-Solutins-CPP-JAVA

groups:
- name: service-heartbeat
  rules:
  - alert: pds_heartbeat_down
    expr: pds_url_heartbeat == 0
    for: 5m
    labels:
      severity: critical
    annotations:
      description: "pds service has no heartbeat for 5 minutes."

  - alert: cds_heartbeat_down
    expr: cds_url_heartbeat == 0
    for: 5m
    labels:
      severity: critical
    annotations:
      description: "cds service has no heartbeat for 5 minutes."
