# WebSocket

<br /> I will assume that no frame will be fragmented (divided into multiple parts). This implies
that every frame should have its FIN bit set and maximum payload length is 125 bytes. Also,
I transfer only text data (opcode=0x1) and handle only received text data (opcode=0x1) or
connection close command (opcode=0x8).
<br /> The language of development is C. 
