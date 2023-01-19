# fluentd_fluentbit

helm install fluentbit fluent/fluent-bit -f fluentbit_old.yaml -n system


helm install fluentd fluent/fluentd -f fluentd_values.yaml -n system

1.Modify the vlaue for host "10.0.10.233" to Open Search IP <IP image.png>




