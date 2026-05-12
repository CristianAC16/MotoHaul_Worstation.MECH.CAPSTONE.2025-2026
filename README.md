<h1>MotoHaul Worstation</h1>
<h2>Mechanical Engineering Capstone 2025-2026</h2>
<h3>Description</h3>
A hitch‑mounted motocross transport and service system designed to safely carry a 250–300 lb motorcycle and function as a trackside maintenance workstation, fully aligned with the project’s engineering requirements and verification plan.
</br>
<br>
<p align="center">
<img src="https://i.imgur.com/RAChJKl.png" height="80%" width="80%" alt="Conceptual CAD"/>
<br/> Overall Look of Design
</p>

<h3>Project Context</h3>

This capstone project required the design, fabrication, and testing of a multi‑functional device that mounts to a standard 2‑inch vehicle receiver hitch. A budget of 800$ was given.
The MotoHaul Workstation integrates:
- A secure motorcycle transport system
- Tie‑down and wheel‑chock safety systems
- A manufacturable steel‑tube frame with a required safety factor ≥ 2.0

These requirements guided every design, analysis, and manufacturing decision.

<h3>My Contributions</h3>

<h4>Research</h4>

- Investigated lifting mechanisms, hitch/shank concepts, and weld design fundamentals.
- Researched vehicle hitch specifications and load‑rating requirements.
- Explored FEA approaches for welded joints and structural members.

<h4>Design</h4>

- Created concept sketches and full CAD assemblies.
- Designed the shank, base plate, winch system, slider mechanism, and platform options.
- Converted early concepts into manufacturable components.

<p align="center">
<img src="https://i.imgur.com/PshsTYl.png" height="80%" width="80%" alt="Final Structure"/>
<br/> Final Design (CAD)
<br />

<p align="center">
<img src="https://i.imgur.com/PuWBxn8.jpeg" height="80%" width="80%" alt="Final Structure"/>
<br/> Final Design (Manufactured)
<br />

<p align="center">
<img src="https://i.imgur.com/YFxZ8Fw.png" height="80%" width="80%" alt="Technical Drawing"/>
<br/> Technical Drawing
<br />

<h4>Documentation</h4>

- Produced PDR, MCR, and PCR reports, design specifications, and project proposals.
- Maintained meeting notes and welding documentation.

<h4>Modification</h4>

- Refined assemblies and corrected non‑manufacturable parts.
- Implemented design revisions and improved component interfaces.

<p align="Center">
  <img src="https://i.imgur.com/Z6Uv1I9.png" height="500px" alt="Pre - Slider Assembly"/>
  <img src="https://i.imgur.com/7gN5vhC.png" height="500px" alt="Post - Slider Assembly"/>  
<br/> 
  <div align="center"><em>
    Slider Modifications
  <br>• Added chain‑bolt tensioners to stabilize the rear bolt and eliminate unwanted play in the slider assembly.
  <br>• Removed excess material to reduce weight and improve manufacturability.
  <br>• Re-used cut material as gussets to increase stiffness without adding cost.
  <br>• Added shims to improve alignment and reduce play in the slider mechanism.
  <br>• Added wear pads to reduce friction and extend component life.
  </em></div>
</p>

<h4>Analysis</h4>

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
    <img src="https://i.imgur.com/Q5Uotvm.png" height="250px">
    <img src="https://i.imgur.com/LvD9TrY.png" height="250px">
  </p>
  <p align="center"><em>Braking load (left) and speed bump load (right) FEA results.</em></p>
  
  <p align="center">
    <img src="https://i.imgur.com/hnLmetc.png" height="400px">
  </p>
  
  <p align="center"><em>First mode shape from modal analysis.</em></p>
  
  <p align="center">
    <img src="https://i.imgur.com/Y7tfSiy.png" height="400px">
  </p>

  <div align="center"><em>
  <p align="center">MATLAB validation of the modal analysis</p>
  The difference between MATLAB and ANSYS results is expected because the MATLAB model used simplified assumptions 
  (lumped mass and reduced stiffness representation), while ANSYS used a full 3D finite‑element model with more accurate boundary conditions.
  </em></div>

<h4>Manufacturing</h4>

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

<h4>Inspection</h4>

- Completed inspection reports and verified fabricated components against drawings.
- Ensured dimensional accuracy and weld‑quality compliance.

<h4>Testing</h4>

- Organizing and interpreting the raw test data.
- Recalculating deflection values using correct load and geometry relationships.
- Performing analytical checks in Excel.
- Comparing the interpreted results with reference ANSYS FEA data.
- Quantifying the percent error, which resulted in strong agreement (2%, 4%, and 13% depending on the load case).

<em>
The physical deflection test had already been completed by teammates, and I assisted by refining the 
interpretation of the recorded measurements so they could be used for analytical and numerical 
validation. I reviewed the raw data, clarified the calculation approach, and extracted meaningful 
deflection values that could be compared against analytical predictions and reference ANSYS FEA 
results (generated by another team member).
</em>

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
