## [rsschodcedeol-cv][https://github.com/bohdanpaduchak]

===

# Bohdan Paduchak

===

## Contacts

- Discord: BohdanPaduchak#1659
- E-mail: bohdanpaduchak@gmail.com
- Tel: +380968134313

## About myself:

I want to learn 'Front-End Development' in **RSSchool!**

## Code example:

```
function match(candidate, job) {
  for (const jobSkill of job.skills) {
    if (!matchJobSkill(candidate, jobSkill)) {
      return false;
    }
  }
  return true;
}

function matchJobSkill(candidate, jobSkill) {
  let subSkill = new Set(jobSkill.substitutions);
  for (const candSkill of candidate.skills) {
    if (candSkill.name === jobSkill.name && candSkill.preference === "avoid") {
      return false;
    }
    if (candSkill.preference === "desired") {
      candSkill.experience = candSkill.experience * 1.5;
    }
    if (!matchExperience(candSkill, jobSkill.idealYears)) {
      return false;
    }
  }
  return true;
}

function matchExperience(candidate, idealYears) {
  if (candidate.experience >= idealYears) {
    return true;
  }
  return false;
}
```

## Work experience:

**Nothing yet…**

## Education and courses:

1.Responsive Web Design, https://www.freecodecamp.org/learn/2022/responsive-web-design/.

2.JavaScript Algorithms and Data Structures, https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/.

3.HTML5/ CSS3/ JAVASCRIPT FUNDAMENTALS, SoftServe IT Academy course.

4.ScriptJedi42, sj42.programmingmentor.com

## Language:

English level - A2
