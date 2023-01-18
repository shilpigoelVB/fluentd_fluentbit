# fluentd_fluentbit

helm install fluentbit fluent/fluent-bit -f fluentbit_old.yaml -n system


helm install fluentd fluent/fluentd -f fluentd_values.yaml -n system

