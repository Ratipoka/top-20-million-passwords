# top_20million_password
This is a list of the top 20 million most used password according to haveibeenpwned. It has been made by cracking passwords in the password list available here : https://haveibeenpwned.com/Passwords. (I've used the ordered by prevelence ntlm version) The passwords are ordered by frequency. If you don't know, Have I Been Pwned is a great website to check if your password has ever apeared in a databreach.
I've been able to crack 98.45% of the top 20 000 000 passwords. The passwords which have not been cracked are available in the not_cracked_hibp_20_ntlm file, the passwords are hashed using ntlm (which is faster to dehash than sha1). The reason why there are fewer than expected passwords in the file is because there are passwords which are similar but don't use the same endoding. I've dedoubled the file to be sure they display only once.

This collection of passwords is only intended for experiment purposes, it's goal is not to make it easier to crack passwords, there are other wordlists online that would make a better job for this.

If you care about your security, I would advise to use a password manager and use 2 factor authentification when ever possible.