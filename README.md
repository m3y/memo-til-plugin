# memo-til-plugin

## Overview
Today I learned

## Install
```
$ cp til $(memo config --cat | grep pluginsdir | awk -F\" '{print $2}')
```
