# HCSP2SystemC
# A tool can transform HCSP into SystemC codes

How to use?
1. compute some necessary parameters using files in 'examples/parameters solver/...' for each case study. ----------more details in 'Readme.txt'.
2. run 'java -jar .../HCSP2SystemC.jar -hcsploc .../xxx.hcsp -delta x -ep x -h x -vep x -T x' to generate SystemC codes from the HCSP system defined in '.../xxx.hcsp'.  ----------'delta', 'ep', 'h' and 'vep' are setted based on the results in step 1; 'T' is the bounded time for execution.  
