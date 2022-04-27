## Prompt:
Given a time in 12-hour AM/PM format, convert it to military (24-hour) time.

# Example: 
Example
s = '12:01:00PM'         Return '12:01:00'.
s = '12:01:00AM'         Return '00:01:00'.


-----------------<>--------------------
# Own solution:

def timeConversion(s):
    if 'AM' in s:
        print(s[:-2])
    if 'PM' in s:
        convert = int(s[:2]) + 12
        print(str(convert) + '' + s[2:-2])

# Test
timeConversion('07:05:45PM')
timeConversion('08:15:20AM')

# Return 
19:05:45
08:15:20


