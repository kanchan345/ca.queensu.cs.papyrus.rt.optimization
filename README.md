
ca.queensu.ca.papyrus.rt.optimization is a build automation and optimization project for models of Embedded Real-time Systems. This project works for models that are built in Eclipse Papyrus for Real-time(Payrus-RT). Papyrus-RT is an Eclipse-based, open-source modelling development environment for UML-RT systems. This project allows the extraction of the model files from an online repository, comparison of the model versions, Impact analysis on compared model version, incremental code generation and patch generation.

**Background**

The following links may provide useful resources regarding the Papyrus-RT, EMF Compare and Epsilon Object Language.

[PapyrusRT Website](https://www.eclipse.org/papyrus-rt/)

[EMF Compare Website](https://www.eclipse.org/emf/compare/)

[Epsilon Object Language](https://www.eclipse.org/epsilon/doc/eol/)


**Running**

Step 1: Open project in Eclipse and run it as plugin project. 

Step 2: Change elements in the model which is built in Papyrus-RT. Push the updated code to git. Run the plug-in project.

Step 3: Provide commit ids of the two model versions, repository path of the model and run the plugin project. Please note: These commit ids can be from any version. The result is the code generation for the changed and impacted elements.











