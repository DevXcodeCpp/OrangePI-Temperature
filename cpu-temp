#!/bin/bash
tput civis 
trap "tput cnorm; echo; exit" SIGINT

while true
do
    raw_temp=$(cat /sys/class/thermal/thermal_zone0/temp)
    temp=$((raw_temp / 1000))
    printf "\r\e[32m[ MONITOR ]\e[0m Время: %s | Температура CPU: \e[31m%s°C\e[0m   " "$(date +%H:%M:%S)" "$temp"
    sleep 1
done
