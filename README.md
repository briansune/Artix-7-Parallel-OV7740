# Artix-7-OV7740-fpga-parallel-camera

This is a renew revision of OV7740 Camera Demonstration from ALINX.

## If this project is constructive, welcome to donate a drink to PayPal.

<img src="https://github.com/briansune/FPGA-Camera-MIPI-DVP-Verilog/assets/29487339/75ccc568-4f17-48a1-b2af-20211f98896c" style="height:20%; width:20%">

# A cheap and verified OV7740: <a href="https://item.taobao.com/item.htm?_u=110quk0kf181&id=731514357758&spm=a1z09.2.0.0.66a82e8dhjMDu7&skuId=5240191879145" target="_blank">Camera Supplier</a>

<img src="https://github.com/briansune/Artix-7-Parallel-OV7740/assets/29487339/160da689-7aae-42ab-b65a-dd476ec1e378" style="height:35%; width:35%">

# If you need the EVB - Email me

<img src="https://github.com/briansune/Artix-7-Parallel-OV7740/assets/29487339/32c6348a-b0c6-4874-9585-bfee1edbf5d0" style="height:35%; width:35%">

### The new EVB uses 1.5V VCore, 3.3V AVDD, and 3V3 IO. This is aligned with the ALINX board IO hw specifications.

<img src="https://github.com/briansune/Artix-7-Parallel-OV7740/assets/29487339/c73bf9a2-11a8-4d13-a83d-e88dcfca0418" style="height:35%; width:35%">

# Hardware Setup - OV7740 (EVB OV7740)

<img src="https://github.com/briansune/Artix-7-Parallel-OV7740/assets/29487339/b0693783-7d54-4f09-bd99-83147e34fb08" style="height:45%; width:45%">

## Preview

| Resolution | Preview |
|:---------------:|:----------------------------------------------------------------:|
| DeBayer - 640x480 | <img src="https://github.com/briansune/Artix-7-Parallel-OV7740/assets/29487339/02401912-feea-43d6-8097-26b66e846116" style="height:45%; width:45%"> |

# Vivado Resources

<img src="https://github.com/briansune/Artix-7-Parallel-OV7740/assets/29487339/4d4479b5-a6bd-492d-962f-214486343de8">

The timing of one node is not met but this is normal as cross-clock-domain ignore is not set in XDC which can be include or use CDC library to remove such warning.
