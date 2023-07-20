# python-intro
# a welcome message 

print (" As the tide washed in, the Dutch Tulip Man faced the ocean: conjoiner rejoinder poisoner concealer revelator.")

# data from user
message_one = input(" please enter any words of affirmation you have ")
message_two = input(" please choose a letter ")

#apa tunacount letters ni ngapi kwa hii string yetu called (message_one)
saw = len(message_one)


# apa napo tunacount i ni ngapi kwa io info user ametupea
dor = message_one.count(message_two)


#apa napo tunacalculate the % of io letter user ametupea apo juu kwa io message flani alitujenga
percentage = dor/saw * 100
type(percentage)

#apa tunaprint vle tumecount io letter user amechagua na percentage ya io letter kwa ile info alitujenga
print(" the count of the letter", message_two, " is ", dor )
print(" the percentage of the letter", message_two, " is ", percentage)

