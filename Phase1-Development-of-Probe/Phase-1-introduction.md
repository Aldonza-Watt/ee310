# Introduction
Phase 1 of the project is developing a probe for detecting the water level of the water tank. As we were not allowed to use actual water tanks for practical simulation, we were asked to use capacitors to act as the water tanks for this project.

With reference to the design meeting, we were given specifications of a typical water tank, with a maximum water level of **2500mm (2.5m)** and a diameter of **3500mm (3.5m)**.

From the design meeting, we were also given 2 types of material for the dielectric part of the probe.
1. Silicone Rubber
2. Polyvinyl chloride (PVC)

In order to select the most suitable dielectric material of the probe, we simulated both materials on a software FEMM, with the model of the probe given from the design meeting. We used Excel spreadsheet to record the charge and stored energy of the dielectric material at a certain water level.

In order to find the suitable material for the dielectric, we used 3 parameters and applied 2 formulae to obtain the capacitance C.

**<u> Parameters: </u>**
1. Charge Q
2. Voltage V
3. Stored energy E

**<u> Formulae applied </u>**
$$ E = \displaystyle \frac{1}{2}CV^2 $$
$$ Q = CV $$

During the design meeting, we were also given specification of the particular water levels of the tank.

| Water level | Medium | Depth (mm) |
| --- | --- | --- |
| 0% Water | Air | 3500
| | Water | 0 |
|20% Water | Air | 2500 |
| | Water | 500 |
| 50% Water | Air | 2250 |
| | Water | 1250 |
| 100% Water | Air | 1000 |
| | Water | 2500 |
