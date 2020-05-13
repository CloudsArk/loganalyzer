# loganalyzer

Analyze access logs (Apache, nginx , load balancers) for quick troubleshoot

## Contentes

1. [Usage](#usage)
    1. [Binaries](#binaries)
        1. [Install](#install)
        1. [Run](#run)
            1. [`top` List top 10 IPs, requests, etc](#top)
            1. [`bandwidth` Calculate total bandwidth](#bandwidth)
            1. [`custom` search for a custom field](#custom)

## Usage

### Binaries

#### Install

Download the most recent release binaries for your OS from https://github.com/mohtork/loganalyzer/releases

Install each binary as follows,

1. Move binary to '/usr/local/bin'
```bash
$ sudo mv loganalyzer /usr/local/bin 
```
2. Verify the binary file is working
```bash
$ loganalyzer --help
Access log analyzer can be used to analyze web servers , load balancers access logs

Usage:
  loganalyzer [flags]
  loganalyzer [command]

Available Commands:
  bandwidth   Print total bandwidth
  custom      Search for a custom field
  help        Help about any command
  top         Print top 10 IPs, Requests , etc

Flags:
  -f, --file string   access log filename
  -h, --help          help for loganalyzer
  -v, --version       version for loganalyzer

Use "loganalyzer [command] --help" for more information about a command.
```



## To Do
- Top IPs location
- Searching for a Specific Time Frame
- Show IPs for top requests

