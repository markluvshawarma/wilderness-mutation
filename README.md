WILDERNESS: MUTATION
General Biology Educational Investigation Game  
Topic: Animal Cell Structure and Function  
Platform: Web-based interactive game made with HTML, CSS, JavaScript, Three.js, and Visual Studio Code
Play the Game
Live Game: https://markluvshawarma.github.io/wilderness-mutation/
WILDERNESS: MUTATION is a scientific wildlife-investigation game where the player takes the role of Jacob Smith, a Wildlife Investigator responding to unusual animal illnesses. Instead of identifying a disease from visible symptoms alone, the player must collect field information, process a tissue sample, enter a reconstructed animal cell through MARS, investigate organelles, review cellular evidence, diagnose a fictional disease, and repair the affected cellular process.
The game's journal-style deduction system is inspired by the evidence-elimination mechanic used in Demonology, adapted here for General Biology and animal-cell learning.
---
Current Prototype - V15.4
The current prototype includes:
Procedural 3D environments for the Field Station, Wildlife Reserve, Laboratory, and MARS cell reconstruction
A randomized seven-case campaign
Four possible wildlife species:
Bilby
Dunnart
Numbat
Long-Necked Turtle
Different habitat areas for each animal
WM News story progression across the campaign
NPC interactions and scientific dialogue
Background music and interaction sound effects
MARS instability events and a restart-MARS-only failure system
Gameplay Flow
1. Field Station
The player reports to Operations, answers the Field Operations phone call, speaks with station personnel, and collects:
Camera
Sample Kit
Thermometer
Flashlight
2. Wildlife Reserve
The player locates the affected animal and performs organism-level investigation:
Camera - frame and photograph the animal; saved images appear in Case Photos
Thermometer - hold the reading until the signal stabilizes
Sample Kit - complete a visual sterile-swab procedure, insert the swab into the collection tube, seal it, and apply the correct case label
Flashlight - illuminate dark areas and reveal tracking signs
Field observations help document the case but are not counted as cellular disease evidence.
3. Laboratory
The collected sample is processed through five interactive laboratory procedures:
Sample Intake - verify the specimen identifier
Cellular Extraction - aspirate, transfer, dispense, and mix the sample
External Scan - capture suspicious tissue regions during a moving scan
Microscopy - adjust focus and visually select an abnormal-looking cell
MARS Calibration - align reconstruction channels before entering the cell
4. MARS Cellular Investigation
The player explores a reconstructed animal cell and investigates organelles using six diagnostic tools.
No.	MARS Tool	Biological Purpose
1	Structural Scanner	Examines organelle shape, size, architecture, and position
2	Bioenergetic Probe	Measures ATP-linked energy output
3	Molecular Fluorescence	Examines proteins, ribosomes, lipids, and cytoskeletal structures
4	Transport Tracer	Tracks vesicle movement and intracellular cargo transport
5	Chemical Analyzer	Measures chemical abnormalities such as oxidative stress and membrane leakage
6	Expression Monitor	Examines transcription, translation, and protein-expression pathways
Every tool has its own interactive procedure. Normal and abnormal findings can both be recorded.
5. Journal Deduction
The player manually highlights exactly three observed results.
One highlighted result does not eliminate any disease.
Disease cross-outs begin only after enough useful evidence has been selected.
Normal results remain highlightable and can act as negative findings.
A correct diagnosis requires the disease and the selected three-result evidence set to match.
6. Cellular Repair
After the correct diagnosis, MARS unlocks the Repair Manipulator and the player repairs the affected cellular process.
---
Fictional Cellular Diseases
Code	Cellular Disease	Core Evidence
MBCS	Mitochondrial Bioenergetic Collapse Syndrome	Cristae Damage, Low ATP Output, High Oxidative Stress
NRBD	Nucleoribosomal Biogenesis Dysregulation	Nucleolus Fragmentation, Low Ribosome Density, Low Protein Synthesis
EPTS	Endomembrane Protein Trafficking Syndrome	RER Protein Buildup, Golgi Distortion, Vesicle Congestion
SELF	Smooth Endoplasmic Lipid Failure	Smooth ER Expansion, Lipid Accumulation, Membrane Leakage
LACD	Lysosomal Autophagic Clearance Deficiency	Lysosome Enlargement, Cellular Debris, Vesicle Congestion
CITC	Cytoskeletal Intracellular Transport Collapse	Broken Cytoskeleton, Organelle Misposition, Vesicle Congestion
NCEI	Nuclear-Cytoplasmic Expression Instability	Abnormal Transcription, Low Protein Synthesis, Abnormal Membrane Proteins
These disease names are fictional and are used only as an educational framework for connecting cellular structures to biological functions.
---
Major Animal-Cell Structures Taught
The game covers:
Cell membrane
Cytoplasm
Nucleus
Nucleolus
Ribosomes
Rough endoplasmic reticulum
Smooth endoplasmic reticulum
Golgi apparatus
Mitochondria
Lysosomes
Vesicles
Cytoskeleton
The game does not teach plant-cell structures.
---
Educational Objectives
The project is designed to help students:
Identify major animal-cell organelles and describe their structures
Explain the function of major animal-cell components
Relate organelle structure to cellular function
Understand ATP production, protein synthesis, intracellular transport, membrane function, recycling, and gene expression
Distinguish organism-level observations from tissue-level and cell-level evidence
Interpret both positive and negative scientific findings
Apply evidence-based reasoning to form a diagnosis
Practice simplified laboratory workflow and sample chain-of-custody
---
Controls
Common controls include:
WASD - Move
Mouse - Look
E - Interact
J - Open Journal
G - Open Equipment Guide
1-4 - Field equipment
1-7 - MARS tools / Repair Manipulator when unlocked
F - Toggle flashlight when available
Some minigames use mouse dragging, clicking, sliders, and timed interactions.
---
Group 4
Markuz Narzoles - Team Leader & Lead Coder
Rod Arzadon - Biology Content Researcher
Trisha Corpuz - Biology Content Researcher
Nikolai Dizon - Assistant Coder
Tyrelle Wandaga - Storyline & Character Development
Khate Agustin - Storyline & Character Development
Tatiana Bernacer - Storyline & Character Development
---
Running Locally
The easiest local method is Visual Studio Code with Live Server.
Place the game file in a folder.
Rename the final release file to `index.html` if desired.
Open the folder in Visual Studio Code.
Start Live Server.
Open the local address shown by Live Server.
The game currently loads Three.js from a CDN, so an internet connection is recommended.
---
GitHub Pages
The public build is hosted at:
https://markluvshawarma.github.io/wilderness-mutation/
The repository's main playable file should be named `index.html` so GitHub Pages loads the game automatically.
