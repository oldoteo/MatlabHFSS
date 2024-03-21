# MatlabHFSS
Set of Matlab functions to performs various tasks in Ansys Electronics Desktop (HFSS), such as drawing coupled microstrip circuits and filters, setting up simulation, ports and graphs.

Run the hfsscoupledmicrostrips script in Matlab (on a computer with a valid Ansys Electronics Desktop license) to see it in action, drawing a sequence of microstrip steps and gaps terminated by two wave ports.
Edit the first lines of parameters to alter the geometry.
The design is entirely parametrized with HFSS variables so that further modifications can be done directly in HFSS and the substrate/airbox resize automatically.

The ancillary functions do the basic operations in HFSS via API, which you can use to achieve other operations in HFSS still Matlab driven.

