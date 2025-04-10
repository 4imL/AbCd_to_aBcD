# AbCd_to_aBcD
대소문자 서로 바꿈
text = input("입력 : ")
str = ""

i = 0
while i  < len(text):
	ch = text[i]
	if ch.isupper() == True :
		ch = ch.lower()
		str += ch
	else :
		ch = ch.upper()
		str += ch
	i += 1

print(str)
		
