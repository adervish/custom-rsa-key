# custom-rsa-key

asn1=SEQUENCE:rsa_key

[rsa_key]
version=INTEGER:0 
modulus=INTEGER:502560410469881 -- semi prime number
pubExp=INTEGER:20454588 
privExp=INTEGER:515960899
p=INTEGER:32452843 -- factor #1
q=INTEGER:15485867 -- factor #2
e1=INTEGER:20454588 
e2=INTEGER:515960899
coeff=INTEGER:14222217 -- invmod(q,p)

-- pubExp and privExp are two numbers such that e1 * e2 mod 1 = (p-1)*(q-1) I used this to find them https://www.cs.drexel.edu/~jpopyack/IntroCS/HW/RSAWorksheet.html


