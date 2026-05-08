<h1>MotoHaul Worstation</h1>
<h2>Mechanical Engineering Capstone 2025-2026</h2>
<h3>Description</h2>
Motorcycle lift designed to be mounted onto the hitch of a car for transport and maintenance of a 300lbs motorcycle.

<p align="center">
<img src="link..." height="80%" width="80%" alt="Conceptual CAD"/>
<br/> Overall Look of Design
<br />

<h3>My Contributions</h2>

Research
- Investigated lifting mechanisms, hitch/shank concepts, and weld design fundamentals.
- Researched vehicle hitch specifications and load‑rating requirements.
- Explored FEA approaches for welded joints and structural members.

Design
- Created concept sketches and full CAD assemblies.
- Designed the shank, base plate, winch system, slider mechanism, and platform options.
- Converted early concepts into manufacturable components.

<p align="center">
<img src="link..." height="80%" width="80%" alt="Final Structure"/>
<br/> Final Design
<br />

<p align="center">
<img src="link..." height="80%" width="80%" alt="Technical Drawing"/>
<br/> Technical Drawing
<br />

Documentation
- Produced PDR, MCR, and PCR reports, design specifications, and project proposals.
- Maintained meeting notes and welding documentation.

Modification
- Refined assemblies and corrected non‑manufacturable parts.
- Implemented design revisions and improved component interfaces.

<p align="Center">
  <img src="link..." height="250px" alt="Pre - Slider Assembly"/>
  <img src="link..." height="250px" alt="Post - Slider Assembly"/>  
<br/> 
  <div align="center"><em>
    Slider Modifications
  <br>• Removed excess material to reduce weight and improve manufacturability.
  <br>• Re-used cut material as gussets to increase stiffness without adding cost.
  <br>• Added shims to improve alignment and reduce play in the slider mechanism.
  <br>• Added wear pads to reduce friction and extend component life.
  </em></div>
</p>

Analysis
- Performed Excel stress calculations and free‑body diagrams.
- Conducted SolidWorks and Ansys FEA (structural, dynamic, modal).
- Validated FEA results using hand calculations and Matlab checks.
- Ran dynamic load simulations for transport conditions.

  ANSYS Load Cases Evaluated:</br>
  The structure was validated under five real‑world loading scenarios to ensure strength, stiffness, and durability:

  1. **[Turning Load](ca://s?q=Turning_load_analysis)** — Evaluated lateral forces during cornering to assess side‑load stability.  
  2. **[Braking Load](ca://s?q=Braking_load_analysis)** — Simulated longitudinal deceleration forces to verify front‑back structural     resistance.  
  3. **[Speed Bump](ca://s?q=Speed_bump_load_case)** — Modeled vertical impact when both wheels hit a bump simultaneously.  
  4. **[One‑Side Speed Bump](ca://s?q=Uneven_speed_bump_analysis)** — Assessed torsional loading when only one wheel encounters a bump.  
  5. **[Modal Analysis](ca://s?q=Modal_analysis_explanation)** — Identified natural frequencies to avoid resonance during operation.
 
  <p align="center">
    <img src="YOUR_BRAKING_IMAGE.png" height="250px">
    <img src="YOUR_SPEEDBUMP_IMAGE.png" height="250px">
  </p>
  
  <p align="center"><em>Braking load (left) and speed bump load (right) FEA results.</em></p>
  <p align="center">
    <img src="YOUR_MODAL_IMAGE.png" height="250px">
  </p>
  
  <p align="center"><em>First mode shape from modal analysis.</em></p>
  
  <p align="center">
    <img src="YOUR_MATLAB_PLOT..." height="260px">
  </p>

  <div align="center"><em>
  <p align="center">MATLAB validation of the modal analysis</p>
  The difference between MATLAB and ANSYS results is expected because the MATLAB model used simplified assumptions 
  (lumped mass and reduced stiffness representation), while ANSYS used a full 3D finite‑element model with more accurate boundary conditions.
  </em></div>

Manufacturing
- Produced manufacturing drawings for the shank tube, winch rods, hook points, and welded assemblies.
- Prepared fabrication packages, secured welding approval, and cut physical parts.

<p align="center">
  <img src="MATERIAL_PREP.png" height="220px">
  <img src="MACHINING.png" height="220px">
  <img src="WELDING.png" height="220px">
</p>

<p align="center"><em>Material preparation, machining, and welding stages.</em></p>

<p align="center">
  <img src="ASSEMBLY.png" height="220px">
  <img src="FINAL_PART.png" height="220px">
</p>

<p align="center"><em>Assembly process and final manufactured component.</em></p>

Inspection
- Completed inspection reports and verified fabricated components against drawings.
- Ensured dimensional accuracy and weld‑quality compliance.

Testing
- Performing analytical calculations in Excel
- Comparing measured results to analytical predictions

<p align="center">
  <img src="TEST_SETUP.png" height="230px">
  <img src="DEFLECTION_MEASUREMENT.png" height="230px">
</p>

<p align="center"><em>Physical deflection test setup and measured displacement.</em></p>

<p align="center">
  <img src="FEA_DEFLECTION.png" height="260px">
</p>

<p align="center"><em>Reference ANSYS FEA deflection results (simulation performed by another team member).</em></p>

<p align="center">
  <img src="DEFLECTION_COMPARISON_PLOT.png" height="260px">
</p>

<p align="center"><em>Comparison between measured deflection, Excel calculations, and reference ANSYS FEA data.</em></p>
