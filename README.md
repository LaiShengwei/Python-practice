# Python-practice
## Sum of Pairs

	def sum_pairs(ints, s):
    	a=set()
    	for i in ints:
        	if s-i in a:
            	return [s-i,i]
        a.add(i)