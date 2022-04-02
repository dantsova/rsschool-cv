# Yana Dantsova
### Software developer

---

### Contacts

- **Location:** Minsk <br>
- **Phone:** +375-29-56-84-302 <br>
- **Email:** yana_dontsova@mail.ru <br>
- **Discord:** [dantsovayana#8533](https://discordapp.com/users/dantsovayana#8533) <br>
- **Github:** [dantsova](https://github.com/dantsova) <br>
- **LinkedIn:** [dantsovayana](https://www.linkedin.com/in/dantsovayana) <br>
- **Telegram:** [dantsovayana](https://www.t.me/dantsovayana) <br>

---

### Profile

I am a sociable person, able to clearly express my thoughts.
I feel comfortable and enjoy working in a team.
I am able to effectively allocate my energy and time, set the priority of tasks in order to complete the work on time.
My advantage is openness to new knowledge and constant development in the professional field.

---

### Skills
- C#
- .NET Core/.NET Framework
- ASP .NET Core, ASP .NET MVC/WebAPI
- JavaScript
- HTML
- CSS
- React
- TypeScript
- SQL
- Git
- Jira/Trello

---

### Code example

**Highest and Lowest:** *In this little assignment you are given a string of space separated numbers, and have to return the highest and lowest number.* <br>
```javascript
function highAndLow(str){
    let arr = str.split(' ');
    let min = parseInt(arr[0]), max = parseInt(arr[0]);
    for(let i=1; i<arr.length; ++i){
        max = parseInt(arr[i])>max ?
            parseInt(arr[i]) : max;
        min = parseInt(arr[i])<min ?
            parseInt(arr[i]) : min;
    }
    return [max, min].join(" ");
}
```

---
