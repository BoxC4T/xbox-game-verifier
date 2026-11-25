## This tool allows you to verify if the files you downloaded for an unnamed xbox game are authentic
exe hash matches the one provided directly <br>
rest of the hashes where built from a hash checked zip to prevent different zip methods causing a false negative <br>
## How to use
1. Download the correct version of the script (linux or windows)
2. Run the script with the location of your game files as the argument (./linux-verify_sha256.sh /path/to/files)
3. Wait, the process takes a while as the math used to verify files has to read the entire 200gb+ folder
4. You're done, a report will be printed showing what files where validated
## Shortcomings
To prevent a certain unnamed company from being able to do anything the script is unable to tell 2 things
1. If the files are named properly
2. What the names of missing files are (only their hashes)
