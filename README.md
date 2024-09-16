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
  - name: train
    num_bytes: 4468330000
    num_examples: 985041
  - name: test
    num_bytes: 449139524
    num_examples: 98862
  - name: validation
    num_bytes: 450648786
    num_examples: 98837
  download_size: 3256994687
  dataset_size: 5368118310
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
  - split: test
    path: data/test-*
  - split: validation
    path: data/validation-*
---
