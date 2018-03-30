# Python-MPI
This repository contains various experiments to get a start doing MPI programming in python.

This project assume the use of Portable Batch System (PBS) for submitting job in Batch mode.
An example PBS script is also provided.

"When computational jobs are submitted to a job queue they wait in the queue until the appropriate computational resources are available. The queuing system which MSI uses is called PBS, which stands for Portable Batch System. To submit a job to a PBS queue users create PBS job scripts."

Important facts:
	1. MPI_Init initialization will be done when we import mpi4py in the python script
	2. 
