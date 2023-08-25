# Usage
```
$ sshifter [hours] [minutes] [seconds] [milliseconds] [INPUT_FULE] [OUTPUT_FILE]
```
# Examples
1. Delay the subtitle by one minute:
```
$ sshifter 0 1 0 0 input.srt output.srt
```
2. Show the subtitle early by one minute:
```
$ sshifter 0 -1 0 0 input.srt output.srt
```
3. Delay the subtitle by 4 milliseconds, three seconds, two minutes and one hour:
```
sshifter 1 2 3 4 input.srt output.srt
```
