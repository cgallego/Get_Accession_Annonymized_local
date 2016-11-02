
A repository for the local anonymization script, to get the code and the required binaries, just clone it:

to test just run the script Pull_Accession_MRI_MARTEL.py:
1.) findscu by CADid and AccessionN
2. Pulls the AccessionN locally
3.) For each Series, performs compulsory anonymization (blanks names and other personal info)

You only have to modify your machine's info inside dictonaries.py:
for example:
my_aet='SMIALBCAD2'
local_port='5006'
hostID = '142.76.30.200'

by Default, images are pull and anonymized inside the script directory. To change this default modify:
img_folder to desired location.


