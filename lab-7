# VLSI7

RCA 

module ripple(sum, carry, a,b, cin);  
input [3:0] sum;  
input carry;  
input [3:0] a,b;  
input cin;  
wire c1,c2,c3;  
fa f1(sum[0],c1,a[0],b[0],cin);  
fa f2(sum[1],c2,a[1],b[1],c1);  
fa f3(sum[2],c3,a[2],b[2],c2);  
fa f4(sum[3],carry,a[3],b[3],c3);  
endmodule
