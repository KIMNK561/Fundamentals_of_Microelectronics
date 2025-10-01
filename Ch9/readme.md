# Cascode stages
&nbsp; By using a degeneration transistor, we can achieve a higher output impedance in a CE/CS stage while requiring a nearly current-independent
headroom, unlike a degeneration resistor whose headroom-consume increases linearly with current. The voltage headroom refers to the upper 
and lower boundaries of the output voltage that must be maintained for the transistors to remain in their intended operating region.

&nbsp; The increased output impedance is useful in many applications, but the most important cases are **current sources and amplifiers**. An 
ideal current source with infinite impedance supplies the same current regardless of voltage changes. For example, once we turn on a faucet, we
would ideally expect the same amount of water to flow whether we attach a long hose or wash our hands directly. In reality, this is not true for
either water taps or electrical circuits, but it is what we aim for. To approximate this behavior, we use the cascode configuration, which adds a
degeneration transistor.

&nbsp; With higher output impedance, we also obtain higher gain, as shown by the equation $A_v=-G_m R_{out}$​. This equation can be derived
by converting the circuit into its Norton equivalent. The transconductance $G_m$  does not change significantly when we add the cascode transistor,
but $R_{out}$ increases greatly. 
