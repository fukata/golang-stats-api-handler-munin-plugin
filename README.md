golang-stats-api-handler-munin-plugin
=====================================

Munin plugin of [golang-stats-api-handler](https://github.com/fukata/golang-stats-api-handler).

## Install

    sudo cp golang_stats_ /usr/share/munin/plugins/
    sudo cp golang_stats.conf /etc/munin/plugin-conf.d/

## Symbolic Link

    sudo ln -snf /usr/share/munin/plugins/golang_stats_ /etc/munin/plugins/golang_stats_${item}

## Customize

    sudo vi /etc/munin/plugin-conf.d/golang_stats.conf
