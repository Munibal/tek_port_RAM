module ram_single #(
  parameter DATA_WIDTH=8,          //veri yolu genişliği
  parameter ADDR_WIDTH=8           //adres yollarının genişliği
)(
  input  [(DATA_WIDTH-1):0] data,  //yazılacak veriler
  input  [(ADDR_WIDTH-1):0] addr,  //adres alma yazma / okuma işlemi
  input                     we,    //yazma etkinleştirme sinyali
  input                     clk,   //saat sinyali
  output [(DATA_WIDTH-1):0] q      //verileri oku
);

  reg [DATA_WIDTH-1:0] ram [2**ADDR_WIDTH-1:0];
  reg [ADDR_WIDTH-1:0] addr_r;

  always @(posedge clk) begin //yazmak
      if (we) begin
          ram[addr] <= data;
      end
      addr_r <= addr;
  end

  assign q = ram[addr_r]; //oku

endmodule