# string-inside-the-function
def string_reverse(str1):                 # defining the function

    rstr1 = ''                           
    index = len(str1)                # count the index value
    while index > 0:
        rstr1 += str1[ index - 1 ]
        index = index - 1
    return rstr1               
str = '1234abcd'            #input
print(str)
print(string_reverse(str))
