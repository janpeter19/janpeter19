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

  **Note 2026-08-21** The setup-scripts for each application have for a long time had a structure of a specific application part and a general part that I call **FMU\_explore**. Now this general part is imported as a separate module file and placed at a central place. This organisation facilitates future maintenance and further development. The setup files are now two smaller files and the setup takes up a few lines in the notebook for clarity. Now for test just for the application BPL\_TEST2\_Batch. The module is done for PyFMI and will later be done also for FMPy. The version is 1.1.0 and have otherwise the same functionality as before. The ideas behind FMU\_explore you find [here](https://www.openmodelica.org/images/M_images/OpenModelicaWorkshop_2022/1505_Axelsson%202022,%20Design%20aspects%20of%20FMU-explore%20a%20Python%20module%20to%20complement%20PyFMI.pdf).

  **Note 2026-07-06** Now applications run with the ltest **FMPy 0.3.30** in Google Colab with Linux. I am happy to see that now also the application BPL\_IEC\_operation also works with this new update of FMPy. However, two new problems arise with applications BPL\_TEST2\_design\_space and BPL\_YEAST\_AIR\_Fedbatch, and these applicatíons worked fine with the previous version of FMPy. The sporadic dialogue with the vendor continues, see [#742](https://github.com/CATIA-Systems/FMPy/issues/742).

  **Note 2026-04-14** Now all Linux FMUs are recompiled with **OpenModelica latest stable version 1.26.3** and using BPL 2.3.2.

  **Note 2026-04-09** Now **BPL 2.3.2** is released and so far only used in application BPL\_YEAST\_AIR\_Fedbatch. Gradually FMUs will be re-compiled. The updated library brings process descriptions and annotation for default values of simulation. This works well in OpenModelica, while for depracated JModelica it does not, and here only used locally for Windows.

  **Note 2026-03-31**
Now applications run with **latest PyFMI 2.21.0 and FMPy 0.3.29** in Google Colab with Linux. The application BPL\_IEC\_operation still has problems using FMPy and works only up to version 0.3.21. The dialogue with the vendor continues. The FMUs are re-compiled now including a description accesible with the command `describe('process')` using the updated FMU-explore 1.0.3.

   Earlier notes you find [here](https://github.com/janpeter19/References/blob/main/Notes.md).

- 💞️ I’m looking forward to collaborate on expanding the examples of use of Modelica in Colab. I also tailor-make models of biotechnical processes for your needs on a consultancy basis. Work with processes involves broader data analysis and is a part of my work, and simulation is just one tool, but an important one. Digital Twins is a catchword these days and part of what I do.

- 📫 You can reach me at: jan.peter.axelsson@vascaia.se

<!---
janpeter19/janpeter19 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
