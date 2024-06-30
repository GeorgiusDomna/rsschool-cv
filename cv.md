# Georgii Domanin

## Contact Information
- TG: +7 (929) 927-3359
- Email: george.domanin@yandex.ru
- Discord: @GeorgiusDomna

## Summary
I am a junior developer with interest in programming and a desire for professional growth.

## Skills
- **Programming Languages:** JavaScript, HTML, CSS
- **Frameworks:** React
- **Version Control Systems:** Git
- **Development Tools:** VS Code

## Code Examples
Example code in JavaScript from Codewars:
```javascript
// Codewars problem: "Complete the solution so that it splits the string into pairs of two characters. If the string contains an odd number of characters then it should replace the missing second character of the final pair with an underscore ('_')."
function solution(str) {
    let result = [];
  
    let arrLett = str.split('');

    for (let i = 0; i < arrLett.length; i += 2) {
        let pair = arrLett.slice(i, i+2).join('');

    if (pair.length === 1) {
        pair += '_';
    }
        result.push(pair);
    }

    return result;
}
```

## Work Experience
- **ToDo App**   
  [Vercel Deploy](https://todo-list-one-lyart.vercel.app/)

## Education
Moscow Technical University of Civil Aviation

## English Language
Level B1.