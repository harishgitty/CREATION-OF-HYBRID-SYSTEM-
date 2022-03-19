# CREATION-OF-HYBRID-SYSTEM-
CREATION OF HYBRID SYSTEM USING SYMMETRIC AND ASYMMETRIC CRYPTOGRAPHY
# Architecture 
![im![image](https://user-images.githubusercontent.com/101494813/159124990-04c5812a-ad9b-45de-a20c-ebd9da23a4a0.png)
age](https://user-images.githubusercontent.com/101494813/159124987-aca3789b-b627-4a6e-9230-8884764f04fb.png)
# ALGORITHM
STEP 1: IMPLEMENT SYMMETRIC ENCRYPTION<br />
STEP 2: ASYMMETRIC KEY GENERATION<br />
STEP 3: IMPLEMENT ASYMMETRIC ENCRYPTION<br />
STEP 4: IMPLEMENT ASYMMETRIC DECRYPTION <br />
STEP 5: IMPLEMENT SYMMETRIC DECRYPTION<br />

# EXPLANATION:
STEP 1: IMPLEMENT SYMMETRIC ENCRYPTION<br />
 
1) After giving the input(message), duplicate the same message 
and perform AND GATE operation.<br />
2) Now perform the output of previous step with the symmetric 
private key in OR GATE operation.<br />
3) Now perform left shift of the previous output and consider it as 
CIPHER TEXT.<br />

STEP 2: ASYMMETRIC KEY GENERATION<br />

Public keys: M, E, P <br />
1)let us consider, P be prime number p=17 and M ∈ P.<br />
2)Lets, take M=3 where m is a primitive element of mod p<br />
Private key: Q<br />
3)Choose Q secret ‘Q’ and compute E ≡M^ Q mod p<br />
4)COMPUTING Q AND E<br />
Choose a random Q =14<br />
Compute e =m ^Q mod p<br />
 =3^14 mod 17<br />
 e=2<br />
5) choose a random key k=8<br />

STEP 3: IMPLEMENT ASYMMETRIC ENCRYPTION<br />

CIPHERTEXT X:<br />
Formulae: Y1=m ^k mod p<br />
 Y2 = X. e ^k mod p<br />
 
STEP 4: IMPLEMENT ASYMMETRIC DECRYPTION<br />

Formula: D (x)=y2 x (y1^Q) ^-1 mod p<br />

STEP 5: IMPLEMENT SYMMETRIC DECRYPTION<br />

1) Now perform right shift to the Asymmetric <br />
Decrypted text.<br />
2) Perform OR GATE for the output of the previous <br />
step with the symmetric private key.<br />
3) Perform AND GATE with the output of the previous 
step and duplicate message.<br />
4) Now, we get the entered original message as <br />
decrypted value<br />
