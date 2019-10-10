Private sub form _click()
dim i as integer ,n as long
for i= 1 to 9999
n=i^2
if (n-i) mod 10 ^ (len(trim(i)))= 0 then 
print i;
end if
next i
print
end sub
