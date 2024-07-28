# Nerdaxe-cgminer
Cgminer for Nerdaxe

Usage:

First run the Auto-Compiler to install the needed dependencies and compile Cgminer.

	$ ./Auto-Compiler

Wait for the Auto-Compiler to finish and then use the Worker Generator to make executable bash file for running miner.

	$ ./Worker-Generator

First, choose a name for the bash script to be saved as, no spaces allowed.

	   Save As:
	 $ Exampe

Second, Insert chosen pool url.

	  Pool URL:
	$ stratum+tcp://jp.stratum.slushpool.com:3333

Third, Insert worker name for selected pool.

	  Pool Worker:
	$ meap10.test

Forth, Insert worker password.

	  Worker Password:
	$ x

Fith, Now you can Insert any extra arguments for cgminer, If none just hit enter.

	  Extra Arguments For cgminer:
	  Example: --suggest-diff 32
	  **If none hit Enter**
	$ 

Once that's done, run the script just made with a ./ infront of the name.

	$ ./Example
