# Countdown

## Description

Countdown is a command line program that tells you how many days are
remaining until any number of events that you've configured. Use it in your
shell's $PS1 to always have the soonest event displayed, or just use it on the
fly whenever you need some encouragement for the week.

![demo](https://user-images.githubusercontent.com/5622404/118373813-932a0780-b56d-11eb-9388-d58adc65b8a6.gif)


## Usage

```text
USAGE:
    countdown [OPTIONS] [SUBCOMMAND]

OPTIONS:
    -h, --help             Print help information
    -n, --n <N>            Max number of events to display
    -o, --order <ORDER>    Specify the ordering of the events returned [possible values: shuffle,
                           time-asc, time-desc]
    -V, --version          Print version information

SUBCOMMANDS:
    add-event    Add new events
    help         Print this message or the help of the given subcommand(s)


Add new events

USAGE:
    countdown add-event --event <EVENT> --date <DATE>

OPTIONS:
    -d, --date <DATE>      Date of event in <dd>-<mm>-<yyyy> ex: 21-3-2133
    -e, --event <EVENT>    Name of event
    -h, --help             Print help information
```

