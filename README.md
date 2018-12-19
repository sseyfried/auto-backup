#!/bin/bash

#This script copies the Downloads directory onto external media

notify-send 'Backup Started' 'Your backup will take a few minutes.'

cp -nRv /home/stephen/Downloads/ /media/stephen/Backup/

notify-send 'Backup Completed' 'Your files have been backed up.'
