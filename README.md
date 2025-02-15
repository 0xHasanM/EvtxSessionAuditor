# EVTX Session Auditor

This tool parses Windows EVTX logs to extract login and logout sessions from a security.evtx file. It uses a Tkinter GUI to let you select the EVTX file and specify a time for correlating login and logout events.

## Features

- Extract login (EventID 4624) and logout events (EventID 4634, 4647)
- Correlate sessions based on a specified UTC time
- Output the correlated sessions to a CSV file

## Requirements

- Python 3.7+
- [tkcalendar](https://pypi.org/project/tkcalendar/)
- [pyevtx](https://pypi.org/project/pyevtx/)
- [lxml](https://pypi.org/project/lxml/)

Install the required packages using:

```bash
pip install -r requirements.txt
