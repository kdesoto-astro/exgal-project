# Final Project for Extragalactic Astronomy
This project adds information about stellar types to our existing semi-analytic model. We assume main sequence evolution and various common initial mass functions to determine the mass distribution of these stellar types at different redshifts/times. We alter the initial code structure to improve modularity and parallelization, allowing for the easy swapping of various IMFs. We also include functions to compare to observations at z=0, and plotting functions.

The coding milestones for this project are:
- [ ] Convert the workbook SAM to a standalone script
- [ ] Add variables that keep track of star masses and ages in each halo
- [ ] Implement Salpeter, Miller-Scalo, & Kroupa IMFs
- [ ] Implement star mass to main sequence lifespan conversion
- [ ] Add variables that track whether star populations are still on main sequence
- [ ] Add approximate star mass to star type conversion for main sequence
- [ ] Star type to color conversion
- [ ] Trace b-r (or other color difference) of halo population over time
- [ ] Add functions importing relevant observations for comparison
- [ ] Add plotting auxiliary functions
- [ ] (optional) improve parallelization of code to run much faster
