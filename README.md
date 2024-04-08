# D_FLIPFLOP
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/4f3e1d9d-e0c3-464e-b0e4-e47946c813bd)
# Truth Table
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/42d38f79-9cc3-4b09-a46f-e0c1241dee57)
# Program
```
module dff(d,clk,rst,Q);
input d,clk,rst;
output reg Q;
always @(posedge clk)
begin
if(rst==1)
Q=1'b0;
else
Q=d;
end
endmodule
```
# Output
![WhatsApp Image 2024-04-08 at 13 51 51_fa518aa8](https://github.com/gokulvenkatesan31/D_FLIPFLOP/assets/123715763/ae09d0a5-f866-4e49-b887-0ff125ed8cc4)
