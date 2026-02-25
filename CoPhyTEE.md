
# CoPhyTEE
## Addressing Covert & Physical Attacks performed from SW in Open-Hardware Trusted Execution Environment-enabled System-on-Chip 

### ANR-23-CE39-0003 ANR-23-CE39-0003-01

Today’s System-on-Chip (SoC) include advanced features that allow for dynamic energy-management to
better adapt to current computation loads, heat, and required performance and energy constraints. However,
an emergent category of attacks has shown that these features can be maliciously exploited to perform
internal attacks (i.e., attacks performed by software co-located with sensitive applications on the same
hardware), even circumventing Trusted Execution Environments (TEE) security guarantees. Reported
attacks include covert channels, Side-Channel Attacks (SCA) and Fault Injection (FI) by exploiting the
frequency, voltage, temperature, current, and power supply. Although totally disabling energy-management
mechanisms would limit and avoid most vulnerabilities, this would go against the performance and energy
optimizations, achieved gains, and might lead to significant overheads.
Instead of limiting or disabling these optimization mechanisms, in CoPhyTEE, we propose to benefit
from them to built a security governor able to detect at run-time possible vulnerable execution scenarios,

### Persons involved in the project
- Dr. **[Maria Méndez Real](https://mariamendezreal.github.io/)**, Université Bretagne Sud - Lab-STICC Lab, **Scientific Leader and Coordinator**
- Dr. Guillaume Bouffard, ANSSI
- Dr. Jean-Christophe Prévotet, INSA de Rennes - IETR
- PhD student Owen Le-Gonidec, Université Bretagne Sud, Lab-STICC
  
### Collaborations

This is within the collaboration with ANSSI. Scientific Advisory Board includes KU Leuven and Radboud University.

### Recent communications and publications

- Scientific conference article accepted at CASCADE: **A Lightweight Embedded Detection System against Voltage Drop Fault Attacks in Multi-Tenant FPGAs**, Le Gonidec, G., Bouffard, G., Prevotet, J. C., & Méndez Real, M. (2026). Springer Constructive Approaches for SeCurity Analysis and Design of Embedded systems (CASCADE).
  
- Scientific journal article accepted at ACM TECS: **Do Not Trust Power Management: A Survey on Internal Energy-based Attacks Circumventing Trusted Execution Environments Security Properties**, Le Gonidec, G., Bouffard, G., Prevotet, J. C., & Méndez Real, M. (2025). ACM Transactions on Embedded Computing Systems (TECS), 24(4), 1-35. [open-version available here](https://doi.org/10.48550/arXiv.2405.15537).

- Presentation and poster at [JAIF](https://jaif.io/2024/) (Journée thématique sur les Attaques par Injection de Fautes), available here; [presentation](/JAIF_GwennLeGonidec.pdf), [poster](/JAIF_Poster.pdf).

### Funding

This project is fund by the Franch Agency of Research ANR. It runs from 2023 - 2027.






