# Implementation of Refined Adaptive RED (RARED) algorithm in ns-3
## Course Code: CS822	<br/>
## Assignment: #GP6	<br/>

### Overview		<br/>
Refined Adaptive RED (RARED) [1] is an extension of ARED [2]. It inherits all the properties of ARED but with a minor improvement in adaptive setting of Pmax. This repository contains an implementation of RARED in ns-3 [3].

### Simulating RARED	<br/>

To simulate RARED algorithm, the attribute RARED must be set to true,
as shown below:

  `Config::SetDefault ("ns3::RedQueueDisc::RARED", BooleanValue (true));`

### RARED example	<br/>

An example program for RARED has been provided in

`src/traffic-control/examples/red-vs-rared.cc`

and should be executed as

`./waf --run "red-vs-rared --queueDiscType=RARED"`

### References         <br/>

[1] Tae-hoon Kim, Kee-hyun Lee, "Refined Adaptive RED in TCP/IP Networks", SICE-ICASE, 2006. International Joint Conference, 2006

[2] S. Floyd, R. Gummadi, and S. Shenker, "Adaptive RED: An Algorithm for Increasing the Robustness of RED's Active Queue Management,", http://www.icir.org/floyd/papers/adaptiveRed.pdf.

[3] http://www.nsnam.org/
