[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/Naereen/ama)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
[![GitHub forks](https://img.shields.io/github/forks/saswatamcode/go-weblookup-cli?)](https://GitHub.com/saswatamcode/go-weblookup-cli/network/)
[![GitHub stars](https://img.shields.io/github/stars/saswatamcode/go-weblookup-cli?)](https://GitHub.com/saswatamcode/go-weblookup-cli/stargazers/)
[![GitHub issues](https://img.shields.io/github/issues/saswatamcode/go-weblookup-cli.svg)](https://GitHub.com/saswatamcode/go-weblookup-cli/issues/)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

# Go WebLookup CLI
A simple CLI written in Go which lets you query IPs, CNAMEs, MX records and name servers for a particular host.

## Usage
NAME:
   WebLookup CLI - Lets you query IPs, CNAMEs, MX records and name servers!

USAGE:
   cli [global options] command [command options] [arguments...]

COMMANDS:
   ns       Looks up the name servers for a Particular Host
   ip       Looks up the IP addresses for a particular host
   cname    Looks up the CNAME for a particular host
   mx       Looks up the MX Records for a particular host
   help, h  Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --help, -h  show help

## Example
![Sample](screenshots/Screenshot.png)


## To Run
- Clone into repo
- Run `go get github.com/urfave/cli`
- Run `go run cli.go` to view usage or `go build cli.go`

