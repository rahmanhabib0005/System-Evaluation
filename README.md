
# Lab Report

## 1. Lab Title
System Performance Evaluation under Idle and Heavy Load Conditions

## 2. Objective
- Measure system performance in idle condition.
- Measure system performance under heavy load.
- Compare and analyze performance differences.

## 3. Tools Required
- Python
- psutil library
- Performance evaluation script

## 4. Procedure

### Step 1: Idle Measurement
- Close unnecessary applications.
- Keep the system in near-idle state.
- Run the performance evaluation program.
- Record CPU, RAM, benchmark, response time and disk speed.

### Step 2: Load Measurement
- Open multiple applications and heavy processes.
- Run the same performance evaluation program.
- Record the same performance metrics.

### Step 3: Comparison

| Metric | Idle | Load | Difference |
|---|---:|---:|---:|
| CPU Usage | 22.02% | 15.50% | 6.52 percentage points |
| RAM Usage | 71.84% | 95.66% | 23.82 percentage points |
| Benchmark Time | 0.070 s | 0.052 s | 0.018 s |
| Response Time | 0.012802 s | 0.012568 s | 0.000234 s |
| Disk Write Speed | 171.36 MB/s | 179.29 MB/s | 7.93 MB/s |
| Disk Read Speed | 390.81 MB/s | 383.79 MB/s | 7.02 MB/s |

### System Configuration

| Component | Specification |
|---|---|
| Operating System | Windows 11 |
| Version | 10.0.26200 |
| Machine | AMD64 |
| Processor | Intel |
| Physical Cores | 6 |
| Logical Cores | 12 |
| Total RAM | 23.95 GB |
| Disk Capacity | 237 GB |

## 5. Analysis Questions

**1. Why does CPU usage increase under load?**

More applications require CPU processing power.

**2. Why does response time become slower?**

Multiple processes compete for system resources.

**3. Which metric is most affected by load?**

RAM utilization shows the largest difference.

**4. Is disk performance affected? Why or why not?**

Yes. Disk read and write speeds can vary under different workloads.

## 6. Conclusion

The experiment compared system performance under idle and heavy-load conditions. RAM utilization increased from 71.84% to 95.66% under heavy load. CPU, response time and disk performance showed variations between the two conditions.
