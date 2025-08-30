# Synchronous-FIFO
First In First Out (FIFO) is a particularly well and practical design concept that serves as a handshaking technique and synchronisation mechanism between two modules.

In Synchronous FIFO, data read and write operations use the same clock frequency. Usually, they are used with high clock frequency to support high-speed systems.

FIFO can store/write the d_in at every posedge of the clock based on wr_en signal till it is full. The write pointer gets incremented on every data write in FIFO memory.

The data can be taken out or read from FIFO at every posedge of the clock based on the rd_en signal till it is empty. The read pointer gets incremented on every data read from FIFO memory.
