### Vẽ lại sơ đồ mạch điện biết mạch có netlist sau:
M1 n0 B n1 n1 PMOS
M2 n1 A 0 0 NMOS
M3 n1 B 0 0 NMOS
M0 VDD A n0 n0 PMOS
M4 VDD n1 OUT OUT PMOS
M5 OUT n1 0 0 NMOS
C1 OUT 0 1nF
.end