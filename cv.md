# Alexander Kovzan
## Power engineer
# Contact Info:
* Location: Belarus, Minsk
* Phone number: +375(29)165-41-95
* E-mail: alexkovzanok@gmail.com
* Telegram: [@gogozucchina](https://t.me/gogozucchina)
* GitHub: [kovzanok](https://github.com/kovzanok)
* Discord: AlexKovzan(kovzanok)#5582
# About myself
I am 22 years old. I've graduated from Belarusian National Technical University this summer. Despite being power engineer, I also wanna try myself in Front-end development. During my university studying I've gain some basic knowledge of algorithms and coding itself. I chose Front-end development because of opportunity to be creative in problem solving.
### Strengths:
* Quick learner
* Team playing
* Hard working
* Desire to develop
# Career
* Technician in [Electrical Department](https://eneca.by/)
* Power engineer in [Operating Department](https://web.minskenergo.by/filialy/minskie-elektricheskie-seti/) 
# Skills and courses
* JavaScript([Fundamentals](https://learn.javascript.ru/))
* Python([Fundamentals](https://stepik.org/course/63085/promo))
* HTML+CSS([Basics](https://stepik.org/course/38218/info))
* Photoshop
* Git/GitHub
# Code Example
[5 kyu kata on Code Wars](https://www.codewars.com/kata/530e15517bc88ac656000716):
ROT13 is a simple letter substitution cipher that replaces a letter with the letter 13 letters after it in the alphabet. ROT13 is an example of the Caesar cipher.

Create a function that takes a string and returns the string ciphered with Rot13. If there are numbers or special characters included in the string, they should be returned as they are. Only letters from the latin/english alphabet should be shifted, like in the original Rot13 "implementation".

```
function rot13(message) {
  let cipher = "";
  for (let index = 0; index < message.length; index++) {
    let symbCode = message.charCodeAt(index);
    let symb = message[index];

    if (symbCode > 77 && symbCode <= 90) { // 
      cipher += String.fromCharCode(65 + (13 - (90 - symbCode + 1))); // 90 is ascii code of Z
    } else if (symbCode > 109 && symbCode <= 122) {
      cipher += String.fromCharCode(97 + (13 - (122 - symbCode + 1))); //122 is ascii code of z
    } else if ( // check is symb is latin/english
      (symbCode >= 65 && symbCode <= 77) || // 65 is ascii code of A
      (symbCode >= 97 && symbCode <= 109) // 97 is ascii code of a
    ) {
      cipher += String.fromCharCode(symbCode + 13); // if symbCode+13 is within A-Z of a-z code range
    } else {
      cipher += symb;
    }
  }
  return cipher;
}
```
# Language
* Russian - native speaker
* English - B2(StreamLine course)

