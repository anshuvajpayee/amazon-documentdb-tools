# Amazon DocumentDB Tools

This repository contains several tools to help users with Amazon DocumentDB including migration, monitoring, and performance. A few of the most popular tools are listed below but there are additional tools in the [migration](./migration), [monitoring](./monitoring), [operations](./operations), and [performance](./performance) folders.

## Amazon DocumentDB Compatibility Tool 

The [DocumentDB Compatibility Tool](./compat-tool) examines log files from MongoDB or source code from MongoDB applications to determine if there are any queries which use operators that are not supported in Amazon DocumentDB.

## Amazon DocumentDB Index Tool 

The [DocumentDB Index Tool](./index-tool) makes it easy to migrate only indexes (not data) between a source MongoDB deployment and an Amazon DocumentDB cluster.

## Prism for Amazon DocumentDB — Well-Architected Lens

[Prism for Amazon DocumentDB](./well-architected/Prism) is an AI-powered tool that runs a **Well-Architected review** of your clusters. It evaluates 75 automated checks across all six AWS Well-Architected Framework pillars — Reliability, Security, Operational Excellence, Performance Efficiency, Cost Optimization, and Sustainability — using AWS APIs and CloudWatch, then produces a health score, prioritized findings with remediation guidance, Bedrock-generated recommendations, and a downloadable PDF report. You can run the review directly from the fleet view for any cluster, without connecting to the database. See the [Prism setup guide](./well-architected/Prism/SETUP.md) to get started.

## Support

The contents of this repository are maintained by Amazon DocumentDB Specialist SAs and are not officially supported by AWS. Please file a [Github Issue](https://github.com/awslabs/amazon-documentdb-tools/issues) if you experience any problems.

## License

This library is licensed under the Apache 2.0 License. 
