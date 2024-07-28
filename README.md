# NerdAxe-cgminer
# !Currently Only Works On Ubuntu 18.0X and Raspberry Pi Buster!
Cgminer for NerdAxe USB Miners

Usage:

First run the Auto-Compiler to install the needed dependencies and compile Cgminer.

	$ ./Auto-Compiler

Wait for the Auto-Compiler to finish and then use the Worker Generator to make executable bash file for running miner.

	$ ./Worker-Generator

First, choose a name for the bash script to be saved as, no spaces allowed.

	   Save As:
	 $ test-run

Second, Insert chosen pool url.

	  Pool URL:
	$ solo.ckpool.org:3333

Third, Insert worker name for selected pool.

	  Pool Worker:
	$ bc1q2ccsfq03emnku5vc0ezkmrnt4vfce0dsnxk02w.NerdAxe

Forth, Insert worker password.

	  Worker Password:
	$ x

Fith, Now you can Insert any extra arguments for cgminer, If none just hit enter.

	  Extra Arguments For cgminer:
	  Example: --suggest-diff 32
	  **If none hit Enter**
	$ --suggest-diff 32

Once that's done, run the script just made with a ./ infront of the name.

	$ ./test-run

If all is done well, you should see something like this.

	  cgminer version 4.12.1-nerdaxe - Started: [2024-07-28 15:56:35.997]
	 --------------------------------------------------------------------------------
	  (5s):0.000 (1m):0.000 (5m):0.000 (15m):0.000 (avg):0.000h/s
	  A:0  R:0  HW:0  WU:0.0/m
	  Connected to solo.ckpool.org diff 32 with stratum as user bc1q2ccsfq03emnku5vc0ezkmrnt4vfce0dsnxk02w.NerdAxe
	  Block: 1f5610b4...  Diff:82T  Started: [15:56:35.605]  Best share: 0
	 --------------------------------------------------------------------------------
	  [U]SB management [P]ool management [S]ettings [D]isplay options [Q]uit
	 --------------------------------------------------------------------------------
	  [2024-07-28 15:56:34.830] Started cgminer 4.12.1-nerdaxe
	  [2024-07-28 15:56:34.830] Probing for an alive pool
	  [2024-07-28 15:56:35.462] Pool 0 difficulty changed to 10000
	  [2024-07-28 15:56:35.533] Pool 0 message: Authorised, welcome to solo bc1q2ccsfq03emnku5vc0ezkmrnt4vfce0dsnxk02w!
	  [2024-07-28 15:56:35.605] Pool 0 difficulty changed to 32
	  [2024-07-28 15:56:35.605] Network diff set to 82T
	  [2024-07-28 15:56:35.996] No devices detected!
	  [2024-07-28 15:56:35.997] Waiting for USB hotplug devices or press q to quit
