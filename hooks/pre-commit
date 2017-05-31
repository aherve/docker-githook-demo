#!/bin/bash
# Lunatic pre-commit hook
echo 'pre-commit hook starting'

FLIP=$(($(($RANDOM%10))%2))

if [ $FLIP -eq 1 ]
then
  echo 'Okay, I will accept your commit'
  exit 0
else
  echo 'Meh. Maybe another time'
  exit 1
fi
