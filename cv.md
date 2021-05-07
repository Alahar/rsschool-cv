# CV

**Name: Sergey Podgayny**

Date of birth: 08.02.1988

---

### Contact Info

- phone: +375291308584
- e-mail: DoctorPo@yandex.ru

---

### Skills

- Familiarity with Java, HTML, SQL GIT, Mercurial, Jira.
- Some experience with Linux. 

#### Code examples

##### Task:

Usually when you buy something, you're asked whether your credit card number, phone number or answer to your most secret question is still correct. However, since someone could look over your shoulder, you don't want that shown on your screen. Instead, we mask it.

Your task is to write a function maskify, which changes all but the last four characters into '#'
  
##### Solution:
  
```java
public class Maskify {
    public static String maskify(String str) {
        
        if (str.length() <4) return str;
        String [] result = str.split("");
        String res = "";
        for (int i = 0; i < result.length - 4; i++) {
                res = res + "#";
            }
            res = res + str.substring(result.length - 4);
             return res;            
       
    }
}
```

More examples of some code I've written can be found following the links:

- [Codewars](https://www.codewars.com/users/Alahar/completed_solutions)

---

### Education

2006 - 2011 - Vitebsk State Medical Institute. Faculty of pharmacy
2011 - 2014 - Belarus State Economic University
---
 
### Foreign Languages

1. **English** - level B1 - B2 (learning as foreign language at school and university; daily use for technical documentation and fiction reading, etc.).
2. **Polish** - level A1 (learning as a second foreign language at school).

---

I had been interested in programming and web developing for some time and about a year ago, I got the opportunity to spend more time on this. Having realized that I liked it way more than my work, I decided to try to do it professionally. Since then I have been studying and applying acquired knowledge.
 
I lack professional experience right now, but I am a fast learner, I like learning something new everyday and putting new knowledge into practice. I believe, I can become a very good web developer. 