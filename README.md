test
====
% time     seconds  usecs/call     calls    errors syscall
------ ----------- ----------- --------- --------- ----------------
  -nan    0.000000           0         1           read
  -nan    0.000000           0         2           open
  -nan    0.000000           0         2           close
  -nan    0.000000           0         2           fstat
  -nan    0.000000           0         8           mmap
  -nan    0.000000           0         3           mprotect
  -nan    0.000000           0         1           munmap
  -nan    0.000000           0         1           brk
  -nan    0.000000           0         4           rt_sigaction
  -nan    0.000000           0         2           rt_sigprocmask
  -nan    0.000000           0         4         4 access
  -nan    0.000000           0         1           clone
  -nan    0.000000           0         1           execve
  -nan    0.000000           0         1           wait4
  -nan    0.000000           0         3           fcntl
  -nan    0.000000           0         1         1 setuid
  -nan    0.000000           0         1         1 setgid
  -nan    0.000000           0         1           arch_prctl
------ ----------- ----------- --------- --------- ----------------
100.00    0.000000                    39         6 total
