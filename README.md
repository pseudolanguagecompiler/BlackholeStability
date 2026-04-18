# Black Hole Stability and Temperature

This note gives a simple way to think about black hole stability as a function of the size of a Blackhole and why this is related to the mass, temperature and total energy in the blackhole, so cannot be easily decreased without putting more energy into the system. 

## Core equations

For a non-rotating black hole:

\[
E = Mc^2
\]

\[
T_H = \frac{\hbar c^3}{8\pi G M k_B}
\]

\[
\frac{dM}{dt} \propto -\frac{1}{M^2}
\]

These show that as mass \(M\) increases, Hawking temperature \(T_H\) decreases, and evaporation slows down.

## Simple stability idea

A very simple stability proxy is:

\[
S \propto \frac{1}{T_H}
\]

Since \(T_H \propto 1/M\), this is also:

\[
S \propto M
\]

So, in this simplified picture, larger black holes are more stable against evaporation.

## Fixed-temperature case

For a Schwarzschild black hole, temperature and mass are linked:

\[
T_H \propto \frac{1}{M}
\]

So if temperature is held fixed, mass is fixed too. That means you cannot change the intrinsic stability of an isolated Schwarzschild black hole without changing the setup.

## Heat capacity

Black holes can have negative heat capacity:

\[
C = \frac{dE}{dT}
\]

For a Schwarzschild black hole, this is negative, which means the black hole gets hotter as it loses energy. That is one reason black hole thermodynamics behaves differently from ordinary systems.

## One-line summary

A simple model is:

\[
S = \frac{1}{T_H} = \frac{8\pi G M k_B}{\hbar c^3}
\]

In this toy model, lower temperature means higher stability.

## Note

This is a simplified thermodynamic picture, not a full general-relativistic stability proof.
