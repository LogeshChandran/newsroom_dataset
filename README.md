---
language:
- en
dataset_info:
  features:
  - name: url
    dtype: string
  - name: archive
    dtype: string
  - name: title
    dtype: string
  - name: date
    dtype: timestamp[ns]
  - name: text
    dtype: string
  - name: summary
    dtype: string
  - name: compression
    dtype: float64
  - name: coverage
    dtype: float64
  - name: density
    dtype: float64
  - name: compression_bin
    dtype: string
  - name: coverage_bin
    dtype: string
  - name: density_bin
    dtype: string
  - name: __index_level_0__
    dtype: int64
  splits:
  - name: test
    num_bytes: 488918254
    num_examples: 108862
  - name: validation
    num_bytes: 489655495
    num_examples: 108837
  download_size: 598742790
  dataset_size: 978573749
configs:
- config_name: default
  data_files:
  - split: test
    path: data/test-*
  - split: validation
    path: data/validation-*
---
