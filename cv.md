
# Ivan Krytski

## Contacts
____

 * Location: Minsk, Belarus
 * Phone: +375 33 688-89-48
 * Email: ivan.kritsckii@yandex.ru
 * GitHub: ivankritsckii

## About Me
____


I am hard-working and responsible person. I often have to deal with difficult situations and take quick decisions.

## Skills
___

* HTML
* CSS
* JavaScript (Basic)
* Git
* Figma

## Code example
___
```
function formatDuration (seconds) {
  if(seconds==0){return 'now'}
  let second = seconds%60;
  let minute = (seconds-second)%3600/60;
  let dMin=seconds-(minute*60)-second;
  let hour = ((dMin)%86400)/3600;
  let dHour = seconds-(hour*3600)-(minute*60)-second;
  let day = (dHour)%(86400*365)/86400;
  let dDay = seconds-(day*86400)-(hour*3600)-(minute*60)-second;
  let year = dDay/(86400*365)
  let res = ''

  let render =(time, string)=>{
    if (time!=0){
    if(time>1){res+= time+ ' ' + string+'s, '}
    else{res+= time+ ' '+ string+', '}
   }
  }
  render(year, 'year')
   render(day, 'day')
   render(hour, 'hour')
   render(minute, 'minute')
   render(second, 'second')
  
  res= res.slice(0,res.length-2)
  let q = res.indexOf(',', res.length-12)
  if(q!=-1){
  let start = res.slice(0,q);
    let end = res.slice(q+1);
    res = start + ' and' + end
   }
  return res
}
```




## Education
___

1. Belarusian state technological university
3. Academy of public administration
2. Rolling-scopes-school

## English
____
**B1** 

## Polish
___
**B2**