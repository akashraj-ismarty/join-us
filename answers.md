About Me:
Hello, I'm Akash Raj, a passionate AR/VR enthusiast cum Unity Developer. I love developing in XR technologies and using these tech to help medical and training industries to come up with new innovations and problem solving solutions.

Yes, I own a Gaming Laptop(ASUS ROG G16) with a RTX 4060 GPU and i7 Intel core 13th Generation.

I did development in both Windows and MacOS for both Android and IOS. including C#, python, and javascript. I primarily use Unity Game Engine alongwith VSCode for my development but I also do coding in FLutter through Android Studio as well.

Social Profile:

StackOverflow Profile: https://stackoverflow.com/users/23954320/akash-raj
Personal Profile: ismarty.co.in

The Real Stuff:
1. Installed Programming Languages : C#, Python, Javascript
   
2. getDigits Function in javascript:

function getDigits(number){
  const numberString = number.toString();
  const digits=[];
  for (let i=0; i< numberString.length; i++){
    digits.push(parseInt(numberString[i]));
  }
  return digits;
}

3. removingDuplicates Function in Python:

def removeDuplicates(arr):
  unique_elements=[]
  for element in arr:
    if element not in unique_elements:
      unique_elements.append(element)
  return unique_elements

4. translateToPigLatin function in Python:

def translateToPigLatin(text):
  words = text.split()
  pig_latin_words = []
  for word in words:
    first_letter=word[0]
    rest_of_word=word[1:]
    pig_latin_word = rest_of_word + first_letter + "ay"
    pig_latin_words.append(pig_latin_word)
  return " ".join(pig_latin_words)
