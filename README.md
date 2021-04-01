String a = "Suite 2khgejkdfjkwehfjkwehfjreggggggggggggggekwefhkwejfh, Level 10, Building A, 12 George St"
String[] b= a.split(',')
String c

print b[0] + "\n"
print b[1]

print "\n"
print b[0].length()

if(b[0].length()>40)
{
     c = b[0].substring(0,40)
    b[1] = b[0].substring(41,b[0].length()) + b[1]
}


print "Value of b[0] is=" + c + "\n" + b[1]
