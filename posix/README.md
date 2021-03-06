# POSIX C API

1.  [main.c](main.c)
1.  [strdup](strdup.c)
1.  [execl](execl.c)
1.  Environment variables
    1.  [environ](environ.c)
    1.  [setenv](setenv.c)
1.  [fork](fork.c)
    1.  [Fork bomb](interactive/fork_bomb.c.off)
    1.  [pipe](pipe.c)
    1.  Semaphores
        1.  [System V semaphores](semaphore_sysv.c)
        1.  semaphore_unnamed.c TODO
        1.  semaphore_named.c TODO. https://stackoverflow.com/questions/16400820/c-how-to-use-posix-semaphores-on-forked-processes
1.  [mmap](mmap.c)
    1.  [shm_open](shm_open.c)
    1.  [MAP_PRIVATE](map_private.c)
1.  [syslog](syslog.c)
1.  [getrusage](getrusage.c)
1.  [pthread](pthread.md)
    1. [pthread_mutex](pthread_mutex.c)
    1. [pthread_tid](pthread_tid.c)
    1. [pthread_deadlock](pthread_deadlock.c)
1.  [Regex](regex.c)
1.  File IO
    1. [write_read](write_read.c)
    1. [mkdir](mkdir.c)
    1. [access](mkdir.c)
    1. [stat](stat.c)
1.  Networking
    1.  [socket](socket/)
    1.  [netdb.h](netdb-h.md)
        1. [gethostbyname](gethostbyname.c)
        1. [gethostname](gethostname.c)
        1. [getservbyport](getservbyport.c)
1.  Signal
    1.  [Kill](kill.c)
    1.  Interactive
        1. [signal_sleep](interactive/signal_sleep.c)
        1. [sigint](interactive/sigint.c)
        1. [signal_fork](interactive/signal_fork.c)
        1.  setpgid
            1. [setpgid.md](interactive/setpgid.md)
            1. [setpgid.c](interactive/setpgid.c)
        1. [alarm](interactive/alarm.c)
1.  Interactive
    1.  [sleep cout](interactive/sleep_count.c)
    1.  [sleep_1](interactive/sleep_1.c)
    1.  [pthread_work](interactive/pthread_work.c)
    1.  [poll](interactive/poll.c)
1.  [Biblography](bibliography.md)
