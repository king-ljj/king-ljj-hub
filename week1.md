module logic_gate_experiment2(

input a, b,
    output led1, led2, led3, led4, led5

);
    assign led1 = a & b; 
    assign led2 = a | b;   
    assign led3 = a ^ b;  
    assign led4 = ~(a | b);
    assign led5 = ~(a & b);
endmodule
