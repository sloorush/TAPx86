# PLAN

- 1 2 3 4 5
- 1 2 3 4 5
- 1 2 3 4 5
- 1 2 3 4 5
- 1 2 3 4 5

alphabet:array=[[a,b,c,d,e],[f,g,h,i,k],[l,m,n,o,p],[q,r,s,t,u],[v,w,x,y,z]]

password:string/int=1112144523

# ALGO

- Parse Password
  READ STRING
  Divide Password into pairs
  for every pair get letter
  append letter to string

- Create password
  READ letters
  DECLARE counter=number of letters
  for every letter get number and

# EXAMPLE

## ENCODEING

word=HELLO

- counter=5

- for counter
  - 5 H
    - GET index for H save in pass
  - 4 E
    - GET index for E append in pass
  - 3 L
    - GET index for L append in pass
  - 2 L
    - GET index for L append in pass
  - 1 O - GET index for O append in pass
- DISPLAY pass

## DECODING(hello)

pass=.. ... . ..... ... . ... . ... ....
pass=2315313134

- counter=len(pass)/2=5
- for counter =
  - 5 23
    - GET index for 23 save in word
  - 4 15
    - GET index for E append in word
      - 3 31
    - GET index for L append in word
  - 2 31
    - GET index for L append in word
  - 1 34 - GET index for O append in word
- DISPLAY word

# PATH TO BUILD

- Create database for static array 3
- make 2 cases for encode/decode 4
- take input word/pass 1
- make algo for encode and decode 5
- display result 2

# ADDITIONAL FEATURES

- light output
- sound output
