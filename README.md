# Boost bandwidth via speedtest
Breaks the bandwidth limitation of Far___Tone.

## Enviroment Setup
1. Install [Termux](https://bit.ly/2SulXt7).
1. Upgrade packages
```bash
pkg upgrade
```
and confirm (press y)

## Dependency
```bash
pkg install python git
```
and confirm (press y)

## Installation
1. Clone the repository
```bash
git clone https://github.com/orz811017/boost_bandwidth_via_speedtest.git
```
1. Check if it's cloned successfully (optional)
```bash
ls
```
Showing `boost_bandwidth_via_speedtest` indicates that cloning in successful.

1. Install it to the system
```bash
cd boost_bandwidth_via_speedtest && python setup.py install
```

## Usage
```bash
speedtest-cli
```
The program will be executed in background.
