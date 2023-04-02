---
title: Exporting Data for External Analysis
sidebar: doc_sidebar
permalink: export-data.html
toc: false
---

# Full-Stack Implementations

## Web Portal

We highly recommend you use the Samsung Health Stack web portal to export your data. The web portal provides a straightforward way to export your data to **.csv** files for further analysis in popular data analysis tools such as SPSS, R, and Matlab. 

To view individual participant records using the web portal:

1. Refer to [Exporting Data for External Analysis](../../portal-guide/results-analysis/exporting-data.md) in the web portal user guide.

> For simple insights into your data from within the web portal, refer to [Running a Data Query](../../portal-guide/results-analysis/running-a-query.md).

## API Endpoints

To export data using the API endpoints:

1. Refer to `POST /projects/{projectId}/graphql` in [Study API Endpoints](../../api-reference/study-api-endpoints.md) and other endpoints in the API reference to fetch the data.
2. Develop your own method to export the data.

# SDK-Only Implementations

Because exporting data is part of the health stack's web portal and does not interface with the participant app, exporting data does not apply to SDK-only implementations. However, you can develop your own method to export the data.