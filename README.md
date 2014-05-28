nanopulse
=========

This C program uses the PWM peripheral to generate precisely timed pulses of very short duration.  Pulses as short as 4 nano seconds can be generated.<br />
<br />
Source: http://abyz.co.uk/rpi/pigpio/code/nanopulse_c.zip
<pre>gcc -o nanopulse nanopulse.c</pre>
Run example (10000 10 nanosecond pulses with 2000 nano second gap)
<pre>./nanopulse 10 10000 2000</pre>
