pass

"""
start 
create private and public gpg keys
"""
gpg --full-gen-key

# see private key
gpg -K

# see secret key
gpg -k

# create password for gmail.com
# this password will be save to folder ~/.password-store in folder Email
pass insert Email/gmail.com
