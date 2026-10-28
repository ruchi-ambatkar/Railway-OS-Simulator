# Algobuzz — Interactive Operating Systems Visualizer
Name : Zubiya Khushgil Khan (24003172)
        Ruchi Ambatkar (24003170)

A local educational visualizer themed around railway reservation and ticket processing.

## Run locally
1. Install Node.js LTS.
2. Open this folder in VS Code.
3. Run `npm start`.
4. Visit http://localhost:3000.

No external npm dependencies are required.

## Simulators
- CPU Scheduling: FCFS, SJF, SRTF, Round Robin, and Priority Scheduling.
- Producer–Consumer: railway request train, bounded buffer, semaphore steps, manual single operations, and independently enabled automatic producer/consumer workers.
- Banker’s Algorithm: Need matrix, safe-sequence analysis, and request evaluation.
- Memory Management: Fixed partitioning and Variable partitioning have distinct allocation models. Fixed partitions are predefined and show internal fragmentation; variable allocation splits dynamically sized free holes. First Fit, Best Fit, and Worst Fit are supported.
- <img width="1515" height="817" alt="image" src="https://github.com/user-attachments/assets/84057e4b-bcd4-4934-9843-eb9576270873" />


History is stored in the current browser using localStorage. This is a local educational simulation, not a live railway booking system.


### Memory Management defaults
- Fixed partitioning divides 1024 KB into four equal 256 KB partitions by default.
- Variable partitioning starts with one contiguous 1024 KB free region and allocates each process exactly its requested size, splitting the remaining free region.
- Default variable-size process requests: 130 KB, 250 KB, 100 KB, and 115 KB.
- Variable partitioning can show external fragmentation when memory is released into separate holes; the current allocation pass illustrates dynamic splitting and free-space tracking.
