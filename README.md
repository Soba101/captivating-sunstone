---
dataset_info:
  features:
  - name: number
    dtype: string
  - name: short_description
    dtype: string
  - name: description
    dtype: string
  - name: urgency
    dtype: int64
  - name: impact
    dtype: int64
  - name: category
    dtype: string
  - name: assignment_group
    dtype: string
  - name: resolution
    dtype: string
  splits:
  - name: train
    num_bytes: 223593
    num_examples: 500
  download_size: 26710
  dataset_size: 223593
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
license: mit
language:
- en
tags:
- synthetic
- support-tickets
- incident-management
pretty_name: Synthetic IT Support Tickets
emoji: 🧾
---

# Synthetic IT Support Tickets

This dataset contains {N} synthetic IT support tickets generated for testing and training ITSM systems like ServiceNow. Each ticket includes fields such as `short_description`, `description`, `urgency`, `impact`, `category`, `assignment_group`, and `resolution`.

## Example

```json
{
  "short_description": "Merchant unable to sign agreement",
  "description": "A merchant reported being unable to e-sign their agreement...",
  "urgency": 2,
  "impact": 1,
  "category": "Software",
  "assignment_group": "IT Support",
  "resolution": "Cleared session cookies and advised the merchant to retry."
}