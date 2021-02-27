# Approach Used:
1. Obtain latitude and longitude of each cab in string format along with their
user-id and name from the JSON encoded input file.

2. Convert latitude and longitude of the cab present in string format to double.

3. Convert latitude and longitude of both, the user and the cab present in
degrees to radians.

4. Calculate distance between the user’s location and the cab using Great Circle
Distance formula.

5. If distance is found to be less than or equal to 50 kms then output the user-
id and name of the cab driver to a new file else take no action.

# Procedure to run the program :
1. Save the code and the file customers.json in a same location.

2. Now, compile the code(using cmd : g++ file_name.cpp) and run it(using cmd : ./a.out /home/gfg/customers.json) with passing file name customers.json along with proper location(e.g. /home/gfg/customers.json).

3. A file named answers.json will be created on the same location where code and customers.json file is existing.