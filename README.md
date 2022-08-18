# Mini_BLHeli_S

The repo is a hardware design for BLHeli BLDC Driver(https://github.com/bitdump/BLHeli) by Kicad 6.0. The design aim to construct a 
SMT module which could be integrated into PCB of Flight Controller or some other DIY projects easily. 

- Pinout class: J
- freq class: H (48Mhz)
- delay class : above 20
- mos: N + P (so there are no mos drivers)
- voltage: 1s-3s(which is limited by LDO, if you use the input 3V3 and don't solder the LDO, then you could use higher voltage. Please be care about withstand voltage of 
input capacities) 

![image](https://github.com/Ncerzzk/Mini_BLHeli_S/blob/master/images/Mini_BLHeli.jpg?raw=true)

![image](https://github.com/Ncerzzk/Mini_BLHeli_S/blob/master/images/Mini_BLHeli2.jpg?raw=true)

## License
Please notice that the license of this project is GPL 3.0. For hardware project, hope that you can share the changes if you make something different in the sch or pcb.




