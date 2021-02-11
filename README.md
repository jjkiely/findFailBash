# findFailBash
A simple bash script using grep to store error messages from pipeline logs in a seperate file for readability,
By default it searches for lines containing ---FAIL: however this can be changed by editing the file.

# Using the script
download or clone it from this repository and run chmod +x findFail.sh
To run the script type ./findFail.sh 'file1' 'file2' where file1 is the source file of the logs and file2 is the file you would like the results to be in
