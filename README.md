## WhiteHat-Crew-CTF2022

## Hi there, let's get a coffee before we start :coffee:

## ScoreBoard
![image](https://i.ibb.co/7KxCPDy/lala.jpg)

## Challenges :

### Forensic :
#### 1. Begginer Forensics
Download Wireshark to analyze .pcap file,

Download the Sample File and Open it with Wireshark

There is supposed to be less than 10 items. Click on everything and find a human readable text.

What does the text said, and what number is the item number is the text? How many rows of the "No." column

Flag Format i.e : WHC{36:Hello it's me}

Flag: ```WHC{4:What, me worry?}```

![images](https://i.ibb.co/y4yMprr/forensic-biginer.jpg)

#### 2. Penceroboh1
WhoRWe

WHC{user:pass}

user starts with: a

pass: WHITEHATCREW

Flag: ```WHC{aoursler:Id10tExpert}```

![images](https://i.ibb.co/KwdF8p6/pen1.png)

#### 3. Penceroboh2
WhoRWe

WHC{user:pass}

user starts with: b

Flag:  ```WHC{brodgers:TheyPlayedWithGreatCharacter}```

![images](https://i.ibb.co/tz5Bp6G/pen2.png)

#### 4. Penceroboh3
WhoRWe

3 Credentials

WHC{user:pass}

Flag: ```WHC{dmoyes:IAmAFootballGeniusowh okay}```

![images](https://i.ibb.co/Lp4LvhB/pen3.jpg)

#### 4. Topi Putih
Apa makna topi putih?

Pass : WHITEHATCREW

Flag: ```WHC{wh1t3_h4t_cr3w!}```

![images](https://i.ibb.co/grjVd3J/topi.jpg)

### 5.  A walk in the park 204 
Classical! Easy just like a walk in the park.

Flag: ```WHC{THE_CLASSIC_STEGANOGRAPHY_EH)```

![images](https://i.ibb.co/k4zP0Tg/meme.jpg)

### Dark Web:
#### 1. TorPaste
We found a dangerous information on the Darknet. Can you please try to obtain the info?

http://torpastezr7464pevuvdjisbvaf4yqi4n7sgz7lkwgqwxznwy5duj4ad.onion/aRr1wftJbeX7cMjQ/

THIS ROOM IS PURELY OPTIONAL IF YOU ARE NOT COMFORTABLE GOING INTO DARK WEB. PLEASE USE VPN + TOR UPON VISITTING THE SITE

Flag: ```WHC{D4RK_W3B_B3G1NN3R}```

![images](https://i.ibb.co/pjgBKxd/147886503-b1cde24b-a154-4759-83a0-00ff3d67b253-1.png)

### Cryptography:
#### 1. Beginner Cryptography
Decode this base64:

YmFzZTY0X2lzX292ZXJyYXRlZA==

Enwrap it in WHC{} like this:-

WHC{your_decoded_text_here}

Flag: ```WHC{base64_is_overrated}```

![images](https://i.ibb.co/w7SBYKG/decode.jpg)

#### 2. Anencephaly
What is this pokemon? 

Flag: ```WHC{APA_KAITAN_DO}```

1. Read file 

![images](https://i.ibb.co/sC2BWDc/anen.jpg)

2. Decode base64

![images](https://i.ibb.co/bFLNSKT/anen2.jpg)

3. Decode Brainfuck

![images](https://i.ibb.co/HtSxJf1/brain.jpg)

4. Decode base64

![images](https://i.ibb.co/xz1SVRV/encode2.jpg)

#### 3. Botak
An old uncle is so tired trying to get his password came to you, he forgot his password. Can you try to brute force his password back?

Flag: ```WCH{unclePenatLahSiapaBuatNiMemangNakKenaPukul}```

![images](https://i.ibb.co/r05t8YF/botak.jpg)

Decode Caesar Chipher

![images](https://i.ibb.co/gTyFwKf/cae.jpg)

#### 4. Xoring
XOR is one of the common way to obfuscate programs and malware from being detect by Anti-Virus Vendor or Yara Rules. By hiding itself from showing and match a certain ruleset, it can flag as malicious file easily to be alert and remove hence XOR is one of the technique used.

Flag: ```WHC{X0R40BFUSC4T10N}```

1. read file

![images](https://i.ibb.co/c84cFsP/xor.jpg)

2. decode Xor

![images](https://i.ibb.co/x2tJ5Wg/xor2.jpg)


### Malware:
#### 1. Malware A - 1

A "not-so-good" developer brought aboard disaster to a common programming language and you guessed it, someone exploit it to create malware.

What is the file SHA256 hash? WHC{SHA256}

WARNING: RUN THE INSPECTION UNDER ISOLATED VIRTUAL MACHINE AS THESE SAMPLES MIGHT STILL BE ACTIVE Pass : infected or WHITEHATCREW

![images](https://i.ibb.co/8cz2TFB/malware-a-1.jpg)

#### 2. Malware A - 2
What is the threat name, hosts and classification?

Format : WHC{threat name|hosts|classification}

[virus total](https://www.virustotal.com/gui/file/ba47f657a4745c96a62c444100d6c38bbff772b47ac03e83dc3ef5d94bc1d77c/community)

![images](https://i.ibb.co/x8kvbPM/test.jpg)

#### 3. Malware a-3
What is the Static File Name? Format: WHC{name.exe}

Flag: ```WHC{0kEuVjiCbh.exe}```

![images](https://i.ibb.co/br9zcnt/virus.jpg)

#### 4. Malware b-1
Lurks in P2P Malignant

What is the name of dropped file process name and it's SHA256? Format: WHC{process:SHA256}

WARNING: RUN THE INSPECTION UNDER ISOLATED VIRTUAL MACHINE AS THESE SAMPLES MIGHT STILL BE ACTIVE Pass : infected

Flag: ```WHC{services.exe:bf316f51d0c345d61eaee3940791b64e81f676e3bca42bad61073227bee6653c}```

![images](https://i.ibb.co/CbPXxwZ/virus2.jpg)

#### 4. Malware b-2
According to JoeSandBox, what is the type of 'Behavior and API' it have?

Example Format: WHC{UPX_Packer} ; put underscore ' _ ' between two words

Flag: ```WHC{API_Interceptor}```

![images](https://i.ibb.co/85BHLhT/api.jpg)


#### Reversing:

### 1. Baby Ransom

Read file r4nsom.py

![images](https://i.ibb.co/QcKWxdM/ransom.jpg)

find encryption key to decrypt Fernet.generate_key() in azman folder,

![images](https://i.ibb.co/QQ9YKxT/ransom2.jpg)

decrypt the file back

![images](https://i.ibb.co/hf1JKB3/ransom4.jpg)













