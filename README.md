# Download-from-YouTube-
def M1():
	from time import sleep
	import time
	import pytube
	str = """
\[\033[1;34m\]    MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
\[\033[1;34m\]    MMMMMMMMMMM                MMMMMMMMMM
\[\033[1;34m\]    MMMN$                           vMMMM
\[\033[1;34m\]    MMMNl  MMMMM             MMMMM  JMMMM
\[\033[1;34m\]    MMMNl  MMMMMMMN       NMMMMMMM  JMMMM
\[\033[1;34m\]    MMMNl  MMMMMMMMMNmmmNMMMMMMMMM  JMMMM
\[\033[1;34m\]    MMMNI  MMMMMMMMMMMMMMMMMMMMMMM  jMMMM
\[\033[1;34m\]    MMMNI  MMMMMMMMMMMMMMMMMMMMMMM  jMMMM
\[\033[1;34m\]    MMMNI  MMMMM   MMMMMMM   MMMMM  jMMMM
\[\033[1;34m\]    MMMNI  MMMMM   MMMMMMM   MMMMM  jMMMM
\[\033[1;31m\]    MMMNI  MMMNM   MMMMMMM   MMMMM  jMMMM
\[\033[1;31m\]    MMMNI  WMMMM   MMMMMMM   MMMM#  JMMMM
\[\033[1;31m\]    MMMMR  ?MMNM             MMMMM .dMMMM
\[\033[1;31m\]    MMMMNm `?MMM             MMMM` dMMMMM
\[\033[1;31m\]    MMMMMMN  ?MM             MM?  NMMMMMN
\[\033[1;31m\]    MMMMMMMMNe                 JMMMMMNMMM
\[\033[1;31m\]    MMMMMMMMMMNm,            eMMMMMNMMNMM
\[\033[1;31m\]    MMMMNNMNMMMMMNx        MMMMMMNMMNMMNM
\[\033[1;31m\]    MMMMMMMMNMMNMMMMm+..+MMNMMNMNMMNMMNMM
\[\033[1;33m\]        https://mrhack0.wordpress.com
"""
	for char in str:
		print (char, end="")
		sleep(.01)
	print("============================================================")

	time.sleep(3)

	print("\n")

	print("\[\033[0;36m\]         Welcom Script download from youtube")

	print("============================================================")

	time.sleep(2)

	print("             Download from YouTube")
	
	print("============================================================")
	
	time.sleep(0)
	
	print("             Please Enter The URL")
	
	url=input("             URL: ")
	
	print("============================================================")
	
	print("             Please wait....")
	
	print("\n")
	
	pytube.YouTube(url).streams.get_highest_resolution().download("YouTube")
	
	print("==========================")
	
	print("             Done..thanks...!")

M1()
