#----------------------------------
#  methods as  string pt 2 
#------------------------------------
# split
a = " rasha mokthar sati"
print(a.split()) #list
a = " rasha-mokthar-sati"
print(a.split("-", 1)) # raut
a = " rasha-mokthar-sati"
#rsplit
print(a.rsplit("-"))
print(a.rsplit("-",1))# lift
# rjust , ljust
print(a.rjust(30))
print(a.rjust(30,'%'))
print(a.ljust(30))
print(a.ljust(30,'%'))
#center
x= "rasha"
print(x.center(10,'#'))
#count
a = " i  r love phython and c++ becouse it is very very very easy"
print(a.count('v'))
print(a.count('r',45,len(a))) # حساس جدا لحاله الاحرف
 # swapcase  تعكس حاله الأحرف
a=' rASha MOKtar SATi'
print(a.swapcase())
# startswith  يبحت عن اول حرف 
a="rasha sati"
print(a.startswith('r',0,len(a)))
#endswith
print(a.endswith('r ',0,len(a)))
#index
print(a.index('r')) #  يتحت ويرجع مكانها وين لو ملقاهاش يطلع eror وميكملش الكود
#find
print(a.find('u')) # يبحت لو ملقاهاش يطلع -1 
#splitlines
a=''' one 
tow
there'''
print(a.splitlines()) # يرجعن عده سطور لسطر واحد ف list 
a='one\ntow\nthre'
print(a.splitlines())  
a='one\ttow\tthre'
#expandtabs 
print(a.expandtabs(20)) # عدد ال فراغات يلي نبيه يحطها ليا
# another  methods 
a= 'is small '
print(a.istitle())
a=''
print(a.isspace())
a=' '
print(a.isspace())
a='jkjfdjs'
print(a.islower())
print(a.isupper())
a='rasjDaafg'
b='taa_kjaj'
c='fajg--kjlkajg'
print(a.isidentifier())
print(b.isidentifier())
print(c.isidentifier())
 # can we name tha varibles like this or not 
print(a.isalpha())
a='jglkjlk000452'
print(a.isalpha())# just alpha
print(a.isalnum())# alpha & numper

#-----------------------

#reples 
a = ' hi my name is rasha hi '
print(a.replace('hi','hellow',1)) #  1  means how many times it changed
print(a.replace('hi','hellow',2))
#join 
a={'one','tow','three'}
print('-'.join(a)) # change list to string 
