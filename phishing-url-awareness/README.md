# EWB Phishing URL Awareness Checker

## Overview
This is a beginner-friendly Python command-line tool that inspects URL text for visible security warning signs. It helps users recognize suspicious patterns in web addresses without opening or connecting to any web links.

## Features
- Detects an @ symbol in the URL
- Flags unusually long URLs (over 100 characters)
- Flags IP-address hostnames
- Flags many hostname segments (5 or more subdomains)
- Flags punycode-style hostnames (xn--)
- Flags the unencrypted HTTP scheme

## Requirements
- Python 3.10 or later
- No third-party packages required (uses built-in Python libraries)

## How to Run
Windows:
```powershell
py phishing_checker.py