# For DL to import all required Libraries
pip install -r requirements.txt

# To compile openMP programs
gcc -o name_for_your_exe_file -fopenmp program_name.cpp -lstdc++

or

g++ -o name_for_your_exe_file -fopenmp program_name.cpp -lstdc++

# To run Executable openMP programs
.\name_of_your_exe_file
