# VLSI-10

8X1MUX 

module mux_8x1(out, i, s);  
output out;  
input [7:0] i;  
input [2:0] s;  
wire w1,w2;  
mux_4x1 m1(w1,i[0],i[1],i[2],i[3],s[0],s[1]);  
mux_4x1 m2(w2,i[4],i[5],i[6],i[7],s[0],s[1]);  
mux_2x1 m3(out,w1,w2,s[2]);  
endmodule
