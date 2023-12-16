# Website Health Checker

Website Health Checker is a simple command-line tool written in Go that checks whether a website is running or is down by attempting to establish a TCP connection to a specified domain and port.

## Usage

1. Make sure you have Go installed on your machine.

2. Clone the repository:
   ```sh
   git clone https://github.com/yaswanth-8/website-health-checker.git

```
cd website-health-checker
go build
./website-health-checker -d google.com
```

-d, --domain: Domain name to be checked (required).
-p, --port: Port number to be checked (optional, default is 80).
