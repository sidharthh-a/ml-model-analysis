# 📊 Memory Profiling of Different File Formats

This project benchmarks the **memory usage and efficiency** of different data storage formats in Python — specifically **JSON**, **Parquet**, and **Feather**.  
The goal is to compare how each format performs in terms of file size, read/write speed, and memory footprint when handling tabular data.

---

## 🚀 Project Overview
Working with large datasets often requires choosing the right storage format to balance:
- **Disk space (file size)**
- **Read/Write performance**
- **Memory efficiency**

This project uses Python tools (`pandas`, `pyarrow`, `fastparquet`, `time`, `memory_profiler`) to:
1. Load data from different formats  
2. Measure memory usage during operations  
3. Compare efficiency across JSON, Parquet, and Feather  

---

## 📂 File Formats Compared
- **JSON**
  - Human-readable, widely used
  - Larger file sizes, slower for large datasets
- **Parquet**
  - Columnar format, compressed
  - Efficient for analytical workloads
- **Feather**
  - Lightweight columnar format
  - Extremely fast read/write, ideal for intermediate data exchange

---

## ⚙️ Setup

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/memory-profiling-formats.git
cd memory-profiling-formats
