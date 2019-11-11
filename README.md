# Lazor
This is Software Carpentry project.<br>
The goal of this project is to build up a code that will automatically find solutions to the “Lazor” game on phones.<br>
You could share the project
## How to use
* The only thing that needs to change is the path for the folder that contains all the .bff file.<br>
* Use python 3.7 to run the code.
## High lights
 * This code will run all possible combinations and the runtime for the largest board yarn_5 is 87.55 seconds.
 * I use Profile package to analysis the time used for each function and optimize the code.
 ## Benchmark
 The detail information for the test run:<br>
   
                          OS:                            Win 10
                          Python version:                3.7
                          CPU:                           Intel Core i5-8300H
                          memory:                        8 GB
                          dark_1
                          run time(seconds):             0.02 s
                          mad_1
                          run time(seconds):             0.13 s
                          mad_4
                          run time(seconds):             3.84 s
                          mad_7
                          run time(seconds):             51.03 s
                          numbered_6
                          run time(seconds):             2.98 s
                          showstopper_4
                          run time(seconds):             0.03 s
                          tiny_5
                          run time(seconds):             0.01 s
                          yarn_5
                          run time(seconds):             87.55 s
                          total run time(seconds):       145.63 s
                          
                          
## Notice
* In the output file:<br>
  > o: valid position<br>
  > x: no block position<br>
  > A: reflect block<br>
  > B: opaque block<br>
  > C: refract block<br>
* This code apply for Lazor boards with reflect, refract, and opaque blocks only.

                          
