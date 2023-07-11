# Port Scanner

The Port Scanner is a simple command-line tool implemented in Rust that scans for open ports on a given IP address. It allows you to specify the number of threads to use for scanning and provides information about the open ports found.

## Usage

To use the Port Scanner, run the following command:

```shell
cargo run [IPADDR] [-j THREADS]
```

## Features
- Multi-threaded scanning: The Port Scanner uses multiple threads to perform parallel port scanning.
- Open port detection: The scanner detects open ports on the specified IP address and displays the port numbers.
- Customizable thread count: You can specify the number of threads to use for scanning.

## Limitations
- The Port Scanner currently supports only IPv4 addresses.
- The Port Scanner does not support scanning port ranges or a range of IP addresses.
