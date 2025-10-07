1) Goal:
   To create a PCB using Altium Designer to gain knowledge on PCB designing and EDA tools. Here, I created a simple function generator using XR2206 IC.
2) Introduction:
    This FG can produce Sine, Triangular, and Square wave outputs of different frequencies. The ultimate goal is to create a fully functional PCB.
3) Components used:
      a) XR2206 IC,
      b) Resistors of desired values,
      c) Capacitors of desired values,
      d) Headers to connect the components with PCB traces and to the external world
4) PCB design:
    This PCB contains the IC, which is connected to fixed resistors and capacitors that define the standard frequency range. The frequency selection can be decided using a jumper that connects the appropriate
    resistor-capacitor pair to meet the desired frequency range. Variable resistors are added to tune the frequency more precisely (like the fine knob of FGs).
5) Design constraints:
    Design constraints for Via hole diameter, trace width, and clearance are obtained from JLCPCB, since they are the manufacturer. Different constraints are defined by different manufacturers. Visit their website
    for better design rules before running DRC.
6) Layer stackup:
    This is a two-layer PCB with Ferrite-4 (FR-4) as the base material. Separated by polyamide dielectric.
  
  
