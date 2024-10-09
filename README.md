## Overview

In this project, we will use Dataflow to collect traffic events from simulated traffic sensor data made available through Google Cloud PubSub, process them into an actionable average, and store the raw data in BigQuery for later analysis. You will learn how to start a Dataflow pipeline, monitor it, and, lastly, optimize it.

## Objectives

1.  Launch Dataflow and run a Dataflow job
2.  Understand how data elements flow through the transformations of a Dataflow pipeline
3.  Connect Dataflow to Pub/Sub and BigQuery
4.  Observe and understand how Dataflow autoscaling adjusts compute resources to process input data optimally
5.  Learn where to find logging information created by Dataflow
6.  Explore metrics and create alerts and dashboards with Cloud Monitoring