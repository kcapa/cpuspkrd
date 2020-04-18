# cpuspkrd
generates Hollywood movie-like CPU noises based on running PID#s

### installation
*requires*: `beep`

clone to /opt/cpuspkrd, or edit `homedir=` in [cpuspkrd.conf](etc/cpuspkrd.conf)

_notes_:
  - requires root access
  - uses debugfs to trace current running PIDs
  - if the target computer was built in the past 5 years, you probably don't have a CPU speaker


### configuration
most commonly you'll find initial tuning needs to be done for optimal "sci-fi"-ness; see the comments in [cpuspkrd.conf](etc/cpuspkrd.conf)

### running
start cpuspkrd with `/path/to/cpuspkrd /path/to/cpuspkrd.conf`

have fun!
