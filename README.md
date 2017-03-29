## PythonFlaskTesting

Resources and Notes from the Python Testing talk I gave at DeveloperWeek 2016 and at other Python User Groups, most recently the March 2017 Philly Python meeting.

- Slides as PDF: [https://github.com/bear/PythonFlaskTesting/raw/master/PythonFlaskTesting.pdf]
- Slide Notes: [https://github.com/bear/PythonFlaskTesting/raw/master/PythonFlaskTesting.txt]
- Tenki Repo: [https://github.com/bear/tenki]
- Video: [https://vimeo.com/heavybit/review/156050325/24eb7154d8]

Articles:
- write article about modern uwsgi and python
  - needs uwsgi v2+ (may require building)
  - needs flask app to be installable (so it lives in the python environment and you don't have to modify pythonpath)
- write article about starting uwsgi in the user/virtualenv
  - upstart, runit, systemd
  - emperor mode vs individual processes https://uwsgi-docs.readthedocs.org/en/latest/Upstart.html
