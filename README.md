# YAST-binary

yast 0.1.0
Cal Yeo
YAST-Yet Another Security Tool

USAGE:
    yast.exe <SUBCOMMAND>

OPTIONS:
    -h, --help       Print help information
    -V, --version    Print version information

SUBCOMMANDS:
    base64
    help       Print this message or the help of the given subcommand(s)
    urlfuzz
  
  
  
  
  
  yast.exe urlfuzz --help
yast.exe-urlfuzz 0.1.0

USAGE:
    yast.exe urlfuzz [OPTIONS] <CMD> <TARGET>

ARGS:
    <CMD>       commands to execute: urlfuzz [default: urlfuzz]
    <TARGET>    target to be fuzzed

OPTIONS:
    -c, --thread <THREAD_COUNT>
            number of threads to use  [default: 1]

    -h, --help
            Print help information

    -p, --protocol <PROTOCOL>
            protocol [default: http]

    -V, --version
            Print version information

    -w, --wordlist <WORDLIST_LOCATION>
            wordlist location eg. /tmp/rockyou.txt [default: rockyou.txt]
