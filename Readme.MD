#What is this project?
use this script to get a pleasant output when executing 
```bash
$docker stats 
```

You can expect an output like:

```
NAME                     CPU %               MEM USAGE / LIMIT     MEM %               NET I/O             BLOCK I/O           PIDS
jira-software-app        2.05%               3.621GiB / 31.26GiB   11.58%              14.3GB / 10.8GB     1.36GB / 590MB      172
bitbucket-app            0.86%               4.138GiB / 31.26GiB   13.24%              28.3GB / 56.3GB     31.5GB / 121GB      333
sonarqube-app            3.00%               1.971GiB / 31.26GiB   6.31%               11.6GB / 7.49GB     1.08GB / 747MB      241
registry-app             0.05%               11.69MiB / 31.26GiB   0.04%               675MB / 745MB       21.2MB / 0B         15
artifactory-app          0.84%               1.251GiB / 31.26GiB   4.00%               1.83GB / 53MB       1.21GB / 1.63MB     81
confluence-app           0.51%               3.763GiB / 31.26GiB   12.04%              17.4GB / 14.9GB     34.8GB / 127GB      168
```