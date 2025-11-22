# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:



## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
```
num=[1]
den=[1 15 50 0]
sys=tf(num,den)
rlocus(sys)
[k poles]=rlocfind(sys)
```
## Output:
<img width="702" height="628" alt="image" src="https://github.com/user-attachments/assets/2e7b2229-12d2-493a-9de0-8f732203a1af" />

## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is ------------
