# gRPC Blockchain Library

## Overview
This project is a custom gRPC library and client built for large-scale blockchain data interactions, designed to overcome limitations seen in existing Python and TypeScript implementations. The library enables efficient, robust data retrieval and processing, making it suitable for high-throughput blockchain indexing.

## Project Goals
- Develop a gRPC library optimized for large-scale data handling
- Address known issues with recursion limits in Python and processing bottlenecks in TypeScript
- Ensure high performance and resilience when handling intensive blockchain data

## Challenges and Considerations
- **Python**: Known recursion limit issues with gRPC deserialization. Use caution when working with large datasets.
- **TypeScript**: Bottlenecks in data processing. Optimizations will be needed to handle large-scale interactions smoothly.

## Future Plans
Explore further optimizations in Rust to improve performance and extend functionality for additional blockchain use cases.
