# accepts-a-string-and-calculate
s = input(&quot;Input a string&quot;)
d=l=0
for c in s:
if c.isdigit():
d=d+1
elif c.isalpha():
l=l+1
else:
pass
print(&quot;Letters&quot;, l)
print(&quot;Digits&quot;, d)
