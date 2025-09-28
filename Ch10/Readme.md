 It is difficult to make perfectly ripple-free DC voltage sources. For example, DC–DC
converters generate voltage by switching current paths. Although a low-pass filter
reduces the ripple, some ripple caused by switching is inevitable. Common-emitter (CE)
and common-source (CS) stages are biased by the supply voltage $V_{CC}$ and the
input common-mode voltage $V_{CM}$ . To suppress the effect of ripples of these
voltage sources on the output, we use a differential pair.

Ideal differential pairs are perfectly symmetric, and the current sources have infinite
impedances. Changes in $V_{CM}$ do not affect the two output nodes so the differential
output does not change (common-mode gain is zero). The only limitation is that $V_{CM}$
must remain within a range that keeps the transistors in the correct operating region.

In practice, however, ideal differential pairs do not exist. First, the current source has
finite impedance. As a result, ripples in $V_{CM}$ appear at the outputs, creating a
nonzero common-mode gain. If the circuit is perfectly symmetric, this does not affect the
differential output. But if asymmetry arises—for example, due to manufacturing 
mismatch—then common-mode gain is converted into differential output. This effect is
called common-mode to differential-mode conversion $A_{CM-DM} = \frac{ΔV_out}{ΔV_CM}$.

A larger differential gain generally leads to a larger $A_{CM-DM}$. The ratio of
differential gain $V_{DM}$ to $A_{CM-DM}$ is the common-mode rejection ratio (CMRR). 
 
