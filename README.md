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

  **Note 2026-10-28**
The following maintenance work has been done. The setup of fmpy notebooks are now done more consistently with "uv pip" and improves the setup speed. Further all setup-files have at the end a clean-up section to delete not necessary variables in the workspace after the fmu_explore class module has been populated with this context information about the application. And that item is now called Application (previously called Adapted). Finally here is progress with using the rudimentary module for OMSimulator and a handful of applications can be run. Good to see that **OMSimulator** handle well also the applications that fmpy has documented problems with!

  **Note 2026-10-05**
I have developed a first prototype fmu_explore_oms that provide the inteface also to OMSimulator.
It is not complete and you only have the functions: par(), init(), newplot(), and simu() at the moment.
Further, the simu() function does not include 'cont'. You can find test notebooks for just a few applications so far BPL_TEST2_Batch, BPL_TEST2_Fedbatch. For the near future the aim is mianly to get this module comparable with the other two. In the longer perspective it would be interesting to expand the usage of FMU_explore to applications with two or more FMUs in combination and here OMSimulator has advantages compared to the other two simulator-enginges.

  **Note 2026-09-28**
Now all applications have been run using **FMU\_explore version 1.2.4** and with the new **default VM Ubuntu 24.04.5 LTS**.
The setup-files for each application are also polished to the Python standard. The latest versions of PyFMI and FMPy have generally been used. However, for FMPy the older version 0.3.29 was needed for two applications as before. I will try to get the developers attention and I hope they think it might be important more generally.

   Earlier notes you find [here](https://github.com/janpeter19/References/blob/main/Notes.md).

- 💞️ I’m looking forward to collaborate on expanding the examples of use of Modelica in Colab. I also tailor-make models of biotechnical processes for your needs on a consultancy basis. Work with processes involves broader data analysis and is a part of my work, and simulation is just one tool, but an important one. Digital Twins is a catchword these days and part of what I do.

- 📫 You can reach me at: jan.peter.axelsson@vascaia.se

<!---
janpeter19/janpeter19 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
