# f5-bigip-decode
Based on instructions at: https://support.f5.com/csp/article/K6917
<br>
Written in Python 3.
<br>
# Usage
bigip-decode.py -c 0000000000.00000.000
<br>
Where -c is your F5 BigIP cookie.
<br>
```
python3 bigip-decode.py -c 2684427692.51205.0000
F5 BigIP cookie:  2684427692.51205.0000
Converted: 172.29.1.160:1480
```
<br>
<br>
Thanks to dsnezhkov (https://github.com/dsnezhkov) for the suggestions and improvements to make the code more efficient.
