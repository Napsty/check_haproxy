# check_haproxy
A fork from Stéphane Urbanovski's HAProxy monitoring plugin. Written in Perl.

## Changes

### 1.1
- Add new option `-i` or `--ignore-backends` to exclude certain backend(s) from the check. 
The parameter expects a single string for the backend name or a list of comma-separated backend names
- Fix and display the maximum number of allowed concurrent sessions of the backend in performance data (was always showing 0 before)
- Added bytes_in and bytes_out to performance data per backend


See https://www.claudiokuenzler.com/blog/897/boosting-check_haproxy-monitoring-plugin-ignore-backends-bytes-performance-data
