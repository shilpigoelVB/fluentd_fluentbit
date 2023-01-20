# fluentd_fluentbit
https://artifacthub.io/packages/helm/fluent/fluent-bit
helm install fluentbit fluent/fluent-bit -f fluentbit_old.yaml -n system

https://artifacthub.io/packages/helm/fluent/fluentd
helm install fluentd fluent/fluentd -f fluentd_values.yaml -n system


-- fluentbit_new_values.yaml
-- fluentd_new_values.yaml
These 2 files are required we don't want the logs to be cascaded inside.

1.Modify the vlaue for host "10.0.10.233" to Open Search IP ->Cluster->Network Details->Private IP




