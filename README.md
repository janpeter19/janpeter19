- 👋 Hi, I’m @janpeter19
- 👀 I’m interested in Modelica and especially biotechnical applications, see
[paper](https://www.researchgate.net/publication/378889007_Design_ideas_behind_Bioprocess_Library_for_Modelica).
- 🌱 I’m currently learning how to reach out more using Google Colab. I have prepared several 
[examples](https://github.com/janpeter19/References/blob/main/Examples_used.md)
for you starting with the repository BPL_TEST2_Batch. Here you follow a Jupyter notebook and can continue interact using Python and modifiy the simulations and graphs shown. More about the technology used
[here](https://github.com/janpeter19/References/blob/main/Technology_used.md) and about the modelling 
[here](https://github.com/janpeter19/References/blob/main/Modelling_used.md).
No installation needed!

   Google Colab major 
   [announcements](https://medium.com/google-colab) and the technical
   [release-notes](https://colab.research.google.com/notebooks/relnotes.ipynb).

  **Note 2025-06-28** Now also the application with PID-control is updated and use BPL 2.3.1. and MSL 4.1.0.

  **Note 2025-06-12** Here are some changes in the Colab environment that makes it difficult to run the demo examples.

   * PyFMI: The script setting up the environment is occasionally very slow. Loading Miniconda used to take 1-2 minuntes but now takes much longer time, but works. Not clear why it is slow.

   * FMPy: The script setting up the environment comes to a halt. Follow the instruction and restart the session.  The the script comes to a new halt. Then just choose the next cell cd BPL_ (and the address depends on the application chosen). Then choose Runtime/Run cell and below.

  Further, I also gradually update the FMUs with MSL 4.1.0. For applications using PID-control that needs an update of BPL and will be done later. This updates should not affect the demo examples here. 

  **Note 2025-03-27** Recently i have made some new bioprocess examples and updated some old, within the current notebooks.

  * BPL\_YEAST\_AIR\_Fedbatch - Here is now a section illustrating the impact of low dissolved oxygen levels in a homogenous bioreactor. 
    This subject is important for understanding scale-up but clear-cut simple dynamic experiments in the lab scale are difficult to find. 
    Instead people in the 80s and 90s focused on the more complicated two-reactor setups. These experiments are the focus of a notebook to 
    be made, before long.

  * BPL\_CHO\_Fedbatch - The model is updated and includes a state for lysed cell mass and the toxic impact that material may have on 
    specific growth rate. Now the simulations can capture the decline of viable cell mass during later part of cultivation often found.

  * BPL\_CHO\_Perfusion\_cspr - This model is also updated and includes a state for lysed cell mass and toxic impact that the material may 
    have. The phenomena is however not yet illustrated in this notebook, but the model is there. Try yourself!

  Further, the PDF-version of notebooks have been updated and corrected and now truncation has been eliminated. Each notebook has been 
  locally printed to a PDF using the package `nbconvert` together with `MikTex` in a Windows environment.

 



   Earlier notes you find [here](https://github.com/janpeter19/References/blob/main/Notes.md).

- 💞️ I’m looking forward to collaborate on expanding the examples of use of Modelica in Colab. I also tailor-make models of biotechnical processes for your needs on a consultancy basis. Work with processes involves broader data analysis and is a part of my work, and simulation is just one tool, but an important one. Digital Twins is a catchword these days and part of what I do.

- 📫 You can reach me at: jan.peter.axelsson@vascaia.se

<!---
janpeter19/janpeter19 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
