# Constant gm rail-to-rail OP-AMP input stage

The purpose of this project is to design a constant-gm rail-to-rail CMOS operational amplifier input stage based on the research paper "Low-voltage constant-gm rail-to-rail CMOS operational amplifier input stage" by Yan Lu and Ruohe Yao (2008). The proposed architecture allows the amplifier to be operated at low voltage levels while maintaining a constant transconductance and rail-to-rail input range. This modified design is intended to trade slightly higher gm variation for lower power consumption. The performance of the modified architecture will be verified through simulation using 0.13μm CMOS technology.

### Circuit Schematic
![alt text](https://user-images.githubusercontent.com/90058055/232256666-76c88fa7-b7ec-400e-9a05-571a0c868944.png "Circuit Schematic")

The output load capacitor represents the compensation capacitor used for the design of the second stage.

### Gm variation with input CM
![alt text](https://user-images.githubusercontent.com/90058055/232256734-c402d689-bc01-49b5-9ac5-ee7decdabc5e.jpg "Gm")


### UGF
![alt text](https://user-images.githubusercontent.com/90058055/232256766-15c6201b-e2a2-408f-a50b-6dceb6fda88c.jpg "GBW")

UGF is nearly constant with input common mode variations due to Gm equalization.
