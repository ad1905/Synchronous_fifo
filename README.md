# Synchronous FIFO
In Synchronous FIFO, data read and write operations use the same clock frequency. Usually, they are used with high clock frequency to support high-speed systems.

## Block Diagram
![blockDiagram](blockDiagram.png)

## Signal 
wr_en: write enable </br>
din[7:0]/wr_data: write data </br>
full: FIFO is full </br>
empty: FIFO is empty </br>
rd_en: read enable </br>
dout[7:0]/rd_data: read data </br>
w_ptr: write pointer </br>
r_ptr: read pointer </br>

## Timing Diagram
![output](timingDiagram.png)
