# siv_tester
*siv_tester* is a test framework for the System Integrity Verifier (SIV) developed in course ET2595 at BTH

The purpose of this framwork is to help the teacher evaluate the submissions. The students can also use it to test their own code before submission. **Please note that this is an automated test. The succesfull execution of your SIV in this framework does not guarantee that your submission fulfills all requirements for a passing grade.**

To get started you just need to download the file `test_siv.py` to one of the virtual machines used in the lab work (I recommend Server A). Place the file preferably in the folder where you have the SIV executable. 

The file `test_siv.py` is a Python script that implements the test framework. Open up a terminal and change directory to the folder where you installed the script. Change the access permission of the script so that is executable: `chmod +x test_siv.py`. Now you can enter the command `./test_siv.py -h` to run the script in help. You will see output as shown below.

```
usage: test_siv.py [-h] -s SIVEXEC [-e ENVDIR] [-i] [-v]

optional arguments:
  -h, --help            show this help message and exit
  -s SIVEXEC, --siv SIVEXEC
  -e ENVDIR, --env ENVDIR
  -i, --init
  -v, --verify
```

*siv_tester* can be executed in fully automated mode or in semi-automatic mode.
