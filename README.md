SPDC heralding analysis based on [Limits on the deterministic creation of pure single-photon states using
parametric down-conversion](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.85.023829)

![image](./output.svg)


## Main Conclusions
- Heralding efficiency is very important. Unless SPDC->Herald Detector efficiency is above 50% or so, the benefit of photon number resolving heralding is minimal. 
- At the time, I was interested in using a high dispersion fiber to convert a wide bandwidth SPDC output into a range of arrival times. So that time resolved heralding (with SNSPD) of the idler could be used to identify the frequency of the corresponding signal photon. This way, a single SNSPD 'scans' the entire idler SPDC spectrum waiting for a photodetection in each clock cycle. The benefit of this is you don't need a detector for each spectral mode. The downside is that if you herald a 2 photon event, you are unable to wait any longer to find a 1 photon event in the same clock cycle, because we assume the detector dead time effectively blinds it from any later modes containing 1 photon. I show in the later parts of this analysis that this downside is not super significant. The main important things are heralding efficiency and number of modes. For mode number higher than 10 or so, $\mu$ for each mode is set low enough that the probability of a $|2\rangle$ detection from any one mode is fairly low. 

TLDR: optimize the SPDC -> Herald detector efficiency. 