# rasp-std-c-serial

This example allows you to test serial tty on Raspebrry PI 2 and 3 without load WiringPi library. Only Unix standard C library is used.

- download source in your wrk directory;
- compile with gcc -c serialTest.c
- link with gcc -o serialTEst serialTest.o
- execute as root to access /dev/tty0 (sudo ./serialTest)

Connect with wire tx pin with rx pin on your Raspberry and you should see the echo transission!
