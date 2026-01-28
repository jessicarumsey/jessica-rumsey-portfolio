# Network Centrality and Robustness Analysis - Enron Email Dataset

## Overview
Analyzed Enron's internal email network to identify key actors and how information and influence were distributed across the organization. Focused on network centrality and robustness. 

## Data & Methods
- Dataset: 500,000 Enron emails (emails.csv)
- Constructed a directed, unweighted network of senders and recipients
- Measured node centrality (degree, closeness, eigenvector, betweenness)
- Tested network robustness by iteratively removing top nodes of each centrality measure

## Key Insights
- Top Executives largely held the highest centrality scores, aligning with the organization's hierarchy
- Enron's communication structure is highly resilient to node removal, showing multiple redundant pathways for information exchange

## Outcome
Produced a comprehensive final report summarizing findings.

## Tools
Jupyter Notebook, R
