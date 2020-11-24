# MOSS
Moss is a plagiarism checker. 

- Download column from Blackboard using “Assignment File Download”
- Unzip the file and move all zip / tar.gz files into
“zipsFromLearn”
- Run ./unzipAndOrganizeXXX.py (Requires Python 2. Moving files
silently fails for some reason using Python 3)
- Clean up zip artifacts
 - rm -rf `find . -name “._*”`
- Upload to moss based on file type
CS350 / SE310
 ./moss -l java `find . -name “*.java”`
CS 432
 NOTE: Using c to best match shaders stored in the HTML files
 ./moss -l c `find . -name "*.html"`
 ./moss -l javascript `fine . -name "*.js"`
