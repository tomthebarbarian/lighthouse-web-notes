# Solving problems with pseudocode.
 15:06
## Loopy Lighthouse instructions
Write a program that prints the numbers from 100 to 200 to the console, with three exceptions: - If the number is a multiple of 3, print the String "Loopy". - If the number is a multiple of 4, print the String "Lighthouse". - If the number is a multiple of both 3 and 4, print the String "LoopyLighthouse".

### Step 1
Understand the problem

* What's the imput?
Range from 100 - 200, have to be explicit here, computers will just count until crash
strings loopy, lighthouse, loopylighthouse
multiples 3 and 4

* What's the output?
try writing out the first few expected results

Prints
lighthouse
101
loopy
103
lighthouse

### Step 2
Try writing pseudo code

write a program printing 100-200

for iterator in range from 100 to 200
  currentiterator  = current step
  print the current iterator
End loops

#### Add some conditions
if num is multiple of 3
  print loopy
else
  print nnum
end if

#### 1 by 1 add all the conditions


#### COnvert you pseudocode ot javascript
Write out your pseudocode using js