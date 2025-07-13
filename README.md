# CahnHilliard_FiniteDifference
Finite difference solver of the Cahn-Hilliard equation (not recommended)

1. Use ch_initialization() to generate initial conditions or read them in from a file.
2. Use CahnHilliard_FD() to solve the Cahn Hilliard equation with a finite difference solver. This function will save phi to a file or output the variables:
    1. t_out: a vector of timepoints
    2. phi_t: a vector of phi over the timepoints
    3. mass_t: a vector of mass over the timepoints
    4. E_t: a vector of discrete energy over the timepoints
3. Optionally, you can make a movie of phi over time by inputting t_out, phi_t, and optional arguments into ch_movie().