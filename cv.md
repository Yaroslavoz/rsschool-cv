# [rsschool-cv](https://rs.school/)  
----  

# **Yaroslav Ozerov**  

## Contact 
---  

- __Location:__ Ukraine
- __Phone:__ +38 (097) 906 25 35
- __Email:__ yaroslavozv@gmail.com
- __Github:__ [Yaroslavoz](https://github.com/Yaroslavoz)

## Summary
---  
Passionate in code-learning and learn-coding  
 Problem solver  
 Great self-management and team-player  
Hope some day to fix some bugs in the Universe code.   
Until then explore the ingredient composition of cookies from the Dark Side.

## Skills
---  
* JavaScript
* React 
* Redux
* MaterialUI
* GraphQL

## Code Example
---  
```
const findFilms = (planetId) => {
    const firstResponse = axios(`https://hw.skillcrucial.com/api/sw/planets/${planetId}/?format=json`)
  .then(item => { return item.data })
  .then(it => {
    return it 
    })
  .then(planet => {  
    return Promise.all(planet.films.reduce((acc, rec) => {
 const filmResponse = axios.get(rec).then(filmObj => filmObj.data)
 return [...acc, filmResponse]
 }, [])).then(filmData => ({ ...planet, films: filmData })) 
 }) 
  
 return firstResponse
}
```  
## Education
---  
* [Skillcrucial](https://skillcrucial.com/)
* [MDN Web Docs](https://developer.mozilla.org/ru/docs/Learn/JavaScript)
* [Youtube](https://www.youtube.com/)
  
## Experience
---  
**2019-2020** - freelance  
**2020-2021** - Skillcrucial, front-end developer

## English
---  
  __B1__

