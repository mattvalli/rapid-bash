# rapid-bash
A set of bash scripts to empower developers to get up and running quickly.

## Installation
For `rapid-bash` to work properly, you must setup a few Environment variables
after installing.

### Mac
On a Mac, we recommend setting up and exporting these variables from one of 
the following locations:
- `~/.bash_profile`
- `~/.bashrc`

```
# Path to the rapid-bash/bin directory
export PATH_RAPID_BASH=<pathname>

# Add this path to the Environment PATH to load the scripts during shell instantiation
export PATH=$PATH_RAPID_BASH:$PATH

# Path to dependencies used in scripts so you can limit to one instance
export PATH_ELASTICSEARCH_HEAD=<pathname>

```

## Scripts
`elasticsearch-client` - Launches AWS elasticsearch-head client UI
