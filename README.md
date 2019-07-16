# jupyterSats [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jongablop/jupyterSats/master?urlpath=%2Fapps%2Faplicacion.ipynb)
Satellite ecosystem for physics orbiting around Jupyter

**Abstract.** We present an interactive tool embed in an electronic laboratory notebook (Jupyter Notebook) that aims to create a good learning experience in the Introductory Physics Laboratory for the first year Physics students. The interaction environment is double: with the experiment; and with the peers in the lab team and the teacher. This interactive environment is very suitable for the teaching-learning process to be effective.

## 1	Introductory Physics Laboratory: Context and background 

The students of the first year of the Physics Grade do not have experience in the laboratory (lab) and their idea of working in the lab is that it does not require an exhaustive prior preparation, as reading the script or to studying/recalling the theoretical foundation of the physical phenomenon that is going to be analysed; they think it is simply going, taking data, writing them down in the notebook and then making (some) calculations. It is a generalized attitude and, even it is even so in other degrees in which the subject of physics is not so well seen/considered, as the degree in chemistry, for example, and in which, in addition, physics lab is not a subject in itself, but it is part of the physics subject and is taught as a magistral lecture. This attitude really makes the work in the lab become a bad experience from which almost all students say they have suffered and barely taken any advantage. On the other hand, and adhering to the data-acquisition-visualization-treatment process, the usual tools available to the students, for the visualization and processing of the data are of general use: they are not specifically designed to take advantage of the experience in the physics lab and/or to deepen in the art of the laboratory work. Finally, the concept of error, and its treatment, is very difficult for students in the first course, so that, they limit themselves to calculating the errors and to give them together with their corresponding values, without thinking about the impact the errors have, what they really mean, or how they could be reduced, or what implies that some are large and others small.

## 2	Our proposal: enhance the learning experience at the Introductory Physics Laboratory

In this work we present a tool (prototype version, still working on it) pertaining to the ecosystem of tools to work in the physics laboratory [2]: the representation and data processing module. It is a module specifically designed to work in a physics lab of the first degree in Physics. It allows to perform all standard operations present in the representation and data processing packages commonly used. However, it posses a fundamental added value for the physics lab, which as far as we know is not present in the traditionally used packages, which makes the tool unique: interactivity at all (needed) levels. The prototype version is still in an exhaustive polish up process carried out in conjunction with a group of students of the 3rd course of the Physics Grade. Their contribution consists of using the tool and criticizing its features.

We show only one example of the possibilities offered by the tool, representation and visualization of the collected data and its adjustment by least squares to a straight line, and the features of interactivity are described. The points can be moved, arbitrarily or restrictedly, and can be added/removed; the errors associated with the points can be varied; the points can be selected and work only with the selected ones; hover can be done, directly access the data and edit them and you can zoom/pan. Any of the those modifies a copy the original data set and constitutes what we call a simulation of the experiment. For each simulation, the fit is updated and can be compared with the experiment or with previous simulations and/or fits; it can be saved. It is possible to simulate data sets under different experimental conditions, to study how the results change with another possible real set of values. Sets of errors for the data can be simulated. The physical magnitude extracted from the linear regression can defined and showed.

It aims to create a good learning experience [3], providing possibilities to develop structured practical activities to deepen the concepts of physics and lab work. It also pursues to occur one of the fundamental parts of physics: the discovery, by allowing students to explore with possibilities of success [4]. In addition, as the exploration is done in-situ, or a priori or a posteriori and since the tool is integrated into the electronic notebook that is shareable, the interaction environment is double: with the experiment; and with the peers in the lab team and the teacher. This interactive environment is very suitable for the teaching-learning process to be effective [4,5].

## 3	Implications and future work 

With the introduction of this tool (and, in its environment) the work in the lab would meet almost the goals of the physics lab [6]: The art of experimentation: the lab should engage each student in significant experiences with experimental processes; Experimental and analytical skills: the lab should help students develop a broad array of basic skills and tools of experimental physics and data analysis; Conceptual learning: the lab should help students master basic physics concepts; Understanding basic knowledge of physics: the lab should help students understand the role of direct observation in physics; Developing collaborative learning skills: the lab should help students develop collaborative learning. We will develop a variant for other degrees, (Chemistry Degree, for which the physics lab is not a subject in itself), with the aim to change the mentioned attitude. In addition, the tool will be developed to be used in upper courses of the Physics Degree: the students will have access to modify the tool itself to meet their needs and will use it for the preparation of the report and presentation of the results.


References 

[1]	M Hanif, PH Sneddon, FM Al-Ahmadi and N Reid, Eur. J. Phys. 30 (2009) 85–96.

[2]	I. Urcelay-Olabarria, R. Lazkoz, J. Urrestilla, A. Leonardo and J.M. Igartua. Proc 9th Int. CSEDU 1, (2017) 458-463.

[3]	T.Fredlund, J. Airey and C. Linder, Eur. J. Phys. 33 (2012) 657–666.

[4]	C. von Aufschnaiter and S.von Aufschnaiter,. 28 (2007) S51–S60.

[5]	D. R. Sokoloff, P. W. Laws and R.K Thornton, Eur. J. Phys. 28 (2007) S83–S94

[6]	American Association of Physics Teachers, American Journal of Physics, Vol. 66(6), 1(998)  483-485.
