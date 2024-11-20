# VLSI8

2X1MUX 

module mux_2x1(y, i0,i1,s);  
output y;  
input i0,i1,s;  
wire sbar;  
assign sbar=~s;  
assign y=(sbar&i0) | (s&i1);  
endmodule
