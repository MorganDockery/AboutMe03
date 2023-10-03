# Morgan's Bio
### *Work Experience*
* General Staff - *Showplace Cinemas* (May 2023-Present)
* Babysitter - *Sorg Residence* (May 2023-August 2023)

### *Education*
* *Evansville Central High School Evansville, IN* 
Graduating May 2025
Core 40 with Academic Honors
GPA: 3.5

* *Southern Indiana Career & Technical Center* 
Finishing May 2025
Computer Science Software Development

>***"He whom lights up the darkness must first be able to see the torch."***
> ***"Oh hey, here it is."*** :flashlight: ***- Me***

>*"I think some of the pressure comes from the expectations of other people." - Barry Bonds*
![Barry Bonds, one of my inspirations](https://encrypted-tbn0.gstatic.com/licensed-image?q=tbn:ANd9GcSLSAeOEK1CCWsjAHaDZJpZxw08-DwSUvFvc9Kw4MI_5E3BUFuyi8iImrMTGa6k_4DHKi_QNmzsGDsSnX4)

| Skills | Qualifications
| --- | --- |
| Python | Adobe Certification |
```Python
Answer = float(text_prompt('Please type a whole number from 1-1000'))
while not Answer == random.randint(1, 1000):
  if Answer < 1:
    # If only one instance of a variable, then functions shouldn't be used.
    Answer = float(text_prompt('Too low. Please type a higher number from 1-20.'))
  if Answer > 1000:
    # If only one instance of a variable, then functions shouldn't be used.
    Answer = float(text_prompt('Too high. Please type a lower number from 1-20.'))
  if not Answer % 1 == 0:
    # If only one instance of a variable, then functions shouldn't be used.
    Answer = float(text_prompt('Not a whole number. Please type a whole number from 1-20.'))
Guess = random.randint(1, 1000)
while Answer != Guess:
  print(Guess)
  UserResponse = text_prompt('I was incorrect. Give me another chance? Y/N')
  if UserResponse != 'Y':
    break
  if Guess > Answer:
    Guess = random.randint(Answer, Guess - 1)
  if Guess < Answer:
    Guess = random.randint(Guess + 1, Answer)
if Answer == Guess:
  print(Guess)
  print('I got it!')
print('Well then, thanks for playing.')```
