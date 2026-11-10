# EWB Phishing URL Awareness Checker

## Overview
Phishing is a trick where a criminal sends a fake link or message to make you share a password, card number or OTP[span_2](start_span)[span_2](end_span). This tool inspects the text of a URL for visible warning signs[span_3](start_span)[span_3](end_span).

## Features
- Detects @ symbol in URL[span_4](start_span)[span_4](end_span)
- Flags unusually long URLs (over 100 characters)[span_5](start_span)[span_5](end_span)
- Flags IP-address hostnames[span_6](start_span)[span_6](end_span)
- Flags many hostname segments (5 or more)[span_7](start_span)[span_7](end_span)
- Flags punycode-style hostnames (xn--)[span_8](start_span)[span_8](end_span)
- Flags HTTP scheme[span_9](start_span)[span_9](end_span)

## Requirements
Python 3.10 or later[span_10](start_span)[span_10](end_span). No extra packages needed[span_11](start_span)[span_11](end_span).

## How to Run
Windows:
```bash
python phishing_checker.py
