# Logging capacity test

This repository creates several EC2 instances which run simple scripts that generate logs and collect performance metrics and server metrics

## Log generator

Log generator is a script which generates random log records
Also collects statistics about those records
And the speed of data generation

That generator needs to be located on the EC2 instance
Prometheus should also collect CPU/Memory and Disk usage from EC2 instance

## Prometheus + Grafana

A separate EC2 instance, which consists of Prometheus + Grafana