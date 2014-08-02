In order to create Poject Thoth filter in python, first write a function which operates on a string.
Next copy and paste the following into your script:



#--------MAIN--------#
import sys #allows reading and writing from and to the sys.stdio streams

#Handle any unexpected exceptions
try:

	line = sys.stdin.readline()
	sys.stdout.write(removeRepetativePunct(line))
	#print("")  #<-- Uncomment to view output

except:

	print("\nUnexpected error:\n",sys.exc_info()[0],"\n")
	raise