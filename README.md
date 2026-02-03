# CTFQuest_Jeeva-Dharshini
ctf_challenge
Challenge Name:The Key in the Frame

Description:
Don't just look at the image; look at the very end of its raw data.

Hint:
Once you find the flag, remember that one layer of encoding might not be enough to hide the truth.

Steps to capture the flag:
1.tail hello.png

Player finds the password for the zipped file in the end of the result of the above command.
Password : IDKPWD

2.Inside the folder named secret, there will be a text file named as flag.

This file contains the double times encoded original flag - "H0IQEKgMZUIsoJSxZ18kqPS9"

3.First the content("H0IQEKgMZUIsoJSxZ18kqPS9") has to be decrypted using ROT13 format.

The output of this step : "U0VDRXtZMHVfbWFkM18xdCF9"

4.Again the last output("U0VDRXtZMHVfbWFkM18xdCF9") has to decrypted using Base64 format.

Now the original flag is obtained in this step.

FLAG: SECE{Y0u_mad3_1t!}
