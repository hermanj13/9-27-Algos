# Bryan's Question

Your task (if you choose to accept it), Write an algorithm that will identify valid IPv4 addresses in dot-decimal format. IPs should be considered valid if they consist of four octets, with values between 0..255 (included).

Input to the function is guaranteed to be a single string.

For example:
```
// valid inputs:
1.2.3.4
123.45.67.89

// invalid inputs:
1.2.3
1.2.3.4.5
123.456.78.90
123.045.067.089
```

Set up:
```
function isValidIP(str) {

}
```

#### Note:
- leading zeros (e.g. 01.02.03.04) are considered *not valid*
