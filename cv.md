# Bondarev Ilya

<img src="https://avatars.githubusercontent.com/u/1894258" alt="Bondarev Ilya's avatar">

💻 Junior Front-End Developer

## Contacts

- **Location:** Russia, Moscow
- **Discord:**: ILUSHKABOND#1580
- **Email:**: ilushkabond@gmail.com

## Summary

For last year I was working as Power BI and Angular Developer. My desire to work as a designer started when I really enjoyed writing code and seeing the changes I made. I've been learning HTML / CSS / JavaScript / PHP / Python / Angular on my own. I'm trying to become a Angular Developer now. Also I want to learn NestJs as second framework.

## Skills

- HTML / CSS
- JavaScript / TypeScript
- Frameworks: Angular, NestJS (in progress)
- Git/ GitHub
- Design program: Figma / Adobe XD
- Web development tools: VSCode, Notepad++

## Experience

- Building Power BI reports using DWH data
- Angular / NestJS / JWT projects

## Code Example

Codewars. "Next bigger number with the same digits" (https://www.codewars.com/kata/55983863da40caa2c900004e).<br>
**Input:** a number<br>
**Output:** a number.

```
const nextBigger = n => {
  let d = n.toString().split('');
  
  let p = -1;
  for (let i = d.length - 1; i > 0; i--) {
    if (+d[i] > +d[i - 1]) {
      p = i - 1;
      break;
    }
  }

  if (p == -1) return p;
  
  let right = d.splice(p);
  let pv = right.splice(0, 1)[0];
  let mm = null, mmi = null;
  
  for (let i = 0; i < right.length; i++) {
    if (right[i] > pv) {
      if (mm == null || right[i] < mm) {
        mm = right[i];
        mmi = i;
      }
    }
  }
  
  if (mmi == null) return -1;
  
  right.splice(mmi, 1);
  right.push(pv);
  right = right.sort();
  
  const ret = +d.concat([mm]).concat(right).join('');
  
  if (ret < n) return -1;
  
  return ret;
}
```

## Education

- **2021 - now**
  - RSSchool: 'JavaScript/Front-end. Stage 0' - **_in progress_**
* **2019 - 2020** Online courses:
  - FreeCodeCamp
  - NodeSchool
* **2015 - 2019**
  - National Research University "Moscow Power Engineering Institute" (MPEI) / Applied Informatics
* **2003 - 2013**
  - Dnipro Scientific Lyceum of Information Technologies (LIT)

## Languages

- **Russian** - native speaker
- **English** - B2 (Intermediate)

## Projects

=> [CV](https://ilushkabond.github.io/rsschool-cv/cv)<br>