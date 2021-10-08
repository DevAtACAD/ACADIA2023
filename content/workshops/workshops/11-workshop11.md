+++
name="The Generative Game"
headerImg="workshop11.jpg"
leaders="""
- **Runjia Tian** ([Machine Learning Researcher Lab for Design Technologies Harvard Graduate School of Design, Boston MA](https://runjiatian.work/))  
- **Zhaoyang Luos** (Ph.D candidate, Graduate Research Assistant and Teaching Fellow Architectural Digital Design and Technology Institute (ADDTI), Harbin Institute of Technology, Harbin, China)
- **Linhai Shen** ([Master in Architecture, Graduate Research Assistant](http://www.forestoshen.com/)) 
"""
keywords=["Computation", "Aggregation", "Assemblies", "Animation", "Simulation", "Grasshopper", "Maya", "MASH", "After Effects", "fields", "forces", "physics", "representation", "Procedural modeling"]

Software=["[Rhino 7 (30 DaysTrial)](https://www.rhino3d.com/download/rhino-for-windows/evaluation)", "[Grasshopper plug-ins](https://www.food4rhino.com/en)",  "[MESH FROM POINTS](https://www.food4rhino.com/app/meshedit#downloads_list)",  "[WEAVERBIRD](http://www.giuliopiacentino.com/weaverbird/)", "[MESH CURVATURE](https://www.food4rhino.com/app/mesh-curvature)", "[PUFFERFISH](https://www.food4rhino.com/app/pufferfish)", "[LUNCHBOX](https://www.food4rhino.com/app/lunchbox)",  "[Autodesk Maya (90 DaysTrial)](https://www.autodesk.com/products/maya/free-trial)",  "[Adobe After Effects (7 Days Trial)](https://www.adobe.com/uk/products/aftereffects.html?mv=search&mv=search&sdid=FHRLZG67&ef_id=Cj0KCQjw5auGBhDEARIsAFyNm9EKiYn-wxw5IQ2hh8_QDZO_TcARxtJ-kysgo7WXBt-fFMm3uRuWYPsaAlXuEALw_wcB:G:s&s_kwcid=AL!3085!3!520815935682!e!!g!!after%20effects%20trial!1422700028!59976298550&gclid=Cj0KCQjw5auGBhDEARIsAFyNm9EKiYn-wxw5IQ2hh8_QDZO_TcARxtJ-kysgo7WXBt-fFMm3uRuWYPsaAlXuEALw_wcB)"] 

prerequisites= ["System requirements_Windows 64-bit Intel or AMD processor (Not ARM) 8 GB memory (RAM) or more is recommended. 600 MB disk space. OpenGL 4.1 capable video card is recommended. 4 GB Video RAM or more recommended. A Multiple-button mouse with a scroll wheel is recommended.  System requirements_Apple Intel Mac 8 GB memory (RAM) or more is recommended. AMD graphics processor recommended on Intel Macs. 5 GB disk space. A Multiple-button mouse with a scroll wheel is recommended  Autodesk Maya_Basic (interface recognition) Rhinoceros & Grasshopper (interface recognition) Adobe After Effects (interface recognition)"]

tentative_workshop_schedule= ["09.11.2021: 10:00 - 18:00 EST", "09.12.2021: 10:00 - 18:00 EST"]

+++

**Abstract**: This 2-day workshop will cover a series of hands-on advanced 3D machine learning techniques for generative architecture design, including but not limited to 2D Latent Walk Techniques, 2.5D Latent Walk Shape Synthesis, 3DGAN and Reinforcement Learning. The workshop will be project based, where participants will be asked to first create datasets or study explicit quantifiable metrics for generative architecture design, and then develop or customize generative architectural designs based on provided sample workflows. 

The workshop will also examine the various types of artificial intelligence that are applied as cutting-edge generative architectural design techniques since the invention of the concept “Computer-Aided Architectural Design” (Mitchell Williams 1975), the paradigm for modern generative architecture design systems. The workshop will reconceptualize Mitchell’s CAAD system consisting of a representation system, a generation system and a testing system into a figurative framework of a generative machine that plays the generative game. The workshop will use this framework to examine state-of-the-art (SOTA) generative architecture design and explore new possibilities beyond existing methods. The workshop will also guide students through the implementation of SOTA systems and experiment with realizing generative design in 3D representations and post-processing results for architecture design with a series of hands-on sessions.


**Description**: The workshop will start with a brief introduction lecture on day one about the overview of the history of generative architecture design, the origin of which dates back to the SketchPad by Ian Sutherland (Sutherland 1964), the Architecture Machine proposed by Nicholas Negroponte in 1970 (Negroponte 1970) and the Computer-Aided Architectural Design Systems by Mitchell Williams in 1975 (Mitchell 1975). Mitchell’s proposal of computer-aided architectural design (CAAD) systems then became the cornerstone paradigm for the modern generative design systems for architecture. Mitchell’s CAAD system is composed of a representation system, a generation system and a testing system. We will use this framework to examine state-of-the-art (SOTA) generative architecture design and explore new possibilities beyond existing methods.

The workshop will guide students through the implementation of SOTA systems and experiment with realizing generative design in 3D representations and post-processing results for architecture design with a series of hands-on sessions. We will provide three tracks as choices for student:

- Track 1: Use image processing to translate 2D generative design to 3D with latent walk techniques
- Track 2: Use 3DGAN for directly implement 3D generative design with voxels
- Track 3: Use the open-source project [RhinoBIM](https://github.com/Archolic95/RhinoBIM) 

Students will learn the following topics in the workshop:
- Track1: 
    - How to use StyleGAN for 2D image generation
    - How to connect StyleGAN to Rhino-Grasshopper for real-time inference and latent walk
  - How to generate 2.5D/3D shape using image processing and image lofting techniques 
- Track 2: 
    - How to use prepare 3D datasets for 3D GAN with binvox
    - How to implement training of 3DGAN with open-source deep learning framework PyTorch
    - How to use 3DGAN for shape synthesis in voxel format and mesh format
    - How to use 3DGAN for real-time inference and visualization with Latent Walk 
- Track 3:
    - Gain basic understanding of reinforcement learning and computational cognitive science 
    - Learn how machine intelligence is used in the AEC industry
