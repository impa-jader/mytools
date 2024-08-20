# mytools
oi
git clone https://github.com/impa-jader/mytools

PI_int= 1415926535897932384626433832795028841971693993751058209749445923078164062862089986280348253421170679
E_int=7182818284590452353602874713526624977572470936999595749669676277240766303535475945713821785251664274
def pi_real(i: int):
    l= len(str(PI_int))
    x=PI_int/10**l
    f=round(3+x,i)
    print(f)

def e_real(i: int):
    l= len(str(E_int))
    x=E_int/10**l
    f=round(2+x,i)
    print(f)
if __name__=="__main__":
    print(len(str(PI_int)))
    print(len(str(E_int)))
    pi_real(100)
    e_real(3)

import mytools as mt
mt.pi_real(10)
mt.e_real(3)
