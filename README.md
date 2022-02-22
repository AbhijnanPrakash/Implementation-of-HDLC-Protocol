# Implementation-of-HDLC-Protocol
High-Level Data Link Control (HDLC) is a bit-oriented code transparent synchronous data link 
layer protocol developed by the International Organization for Standardization (ISO). HDLC is 
used to connect one device to another, using what is known as Asynchronous Balanced Mode 
(ABM). HDLC is based on IBM’s Systems Network Architecture (SNA). HDLC is the default 
encapsulation for serial interfaces on Cisco routers. 
HDLC Protocol is used to send the data in the form of frames; a controller controls the flow of 
data in the data link layer of the OSI model. HDLC protocol is used to transmit frames in the 
logic link layer of the Data link Layer. HDLC frame consists of an 8 bit Flag bit as 01111110, 
followed by control bits, information bits, FCS bits (CRC), address bits and terminates with flag 
bit. It involves the processing of data before transmission, termed as Zero Stuffing, which is a 
special feature of HDLC protocol. A FIFO is used to transmit the data in the order of First in First 
out (FIFO). When complete data is transmitted, FIFO generates an empty signal and the 
transmission of FCS, control, information and address bits begin. On the receiver side, detection 
of flag bits marks the beginning of a new frame and zero un stuffing of data is performed. The 
unstuffed data is stored in variable-length memory.
