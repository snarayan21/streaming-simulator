# 🤖 Streaming Simulator
A simulator for throughput and network use with MosaicML's [Streaming](https://github.com/mosaicml/streaming). The simulator allows you to:
- Plan runs and anticipate issues beforehand
- Find optimal run configurations
- Debug issues with underperforming runs
- Better understand the impact of different configurations

## 🚀 Getting Started
Run the commands below to get simulating!
```
git clone https://github.com/snarayan21/streaming-simulator.git
cd streaming-simulator
make simulation
```
## 🔑 Key Features
### Throughput Estimation
Throughput is estimated for the duration of the run and is displayed as the simulation progresses. We estimate throughput by iterating over the samples of the dataset in order, and performing shard downloads based on an estimate of network bandwidth.

![alt text](https://github.com/[snarayan21]/[streaming-simulator]/blob/[main]/imgs/throughput.png?raw=true)


