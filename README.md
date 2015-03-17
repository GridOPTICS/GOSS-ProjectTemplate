# GOSS-Templates
This template project provides a very easy way to get up and running with GOSS.  GOSS requires java 1.8 sdk to run and requires an eclipse luna to develop in (others can be used, but the tooling we use is specific to eclipse).  There are two plugins that we use exclusively for our environment BNDTools and Amdatu see steps 1-3 from (https://github.com/GridOPTICS/GOSS/wiki/How-To-Setup-GOSS-for-development-in-Eclipse) for specific instructions on setting up an environment.  

 1. Clone this repository git clone https://github.com/GridOPTICS/GOSS-Templates
 2. Open a new eclipse workspace.
 3. Import the cnf and pnnl.goss.template.project
 4. Right click on run.bnd.bndrun Run As -> Bnd OSGi Run Launcher

In the console type gs:listDataSources or gs:listHandlers.  These two commands will give you diagnostics into goss to make sure that things are working properly.

 1. Once verified that everything works properly, rename pnnl.goss.template.project to your own namespace.
 2. Change the git repository to one that you have accesss to and commit it.
 3. Add handlers/datasources/authentication realms to  your project.

 
