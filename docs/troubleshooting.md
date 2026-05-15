Issue:
GPO was not applying to CLIENT01

Root Cause:
The GPO was configured under Computer Configuration, but the computer object was not located inside the target OU.

Resolution:
Moved CLIENT01 computer object into the IT OU and forced Group Policy update using:

gpupdate /force
