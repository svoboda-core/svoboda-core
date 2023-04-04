# Glory To Ukraine! Glory to the heroes.
# Hi there 👋 my name Vasily Konoval
---
### Python Developer | Frontend Developer
---

### Contact information:
* **Location:** Dnipro, Ukraine<br>
* **E-mail:** vasilykonoval@gmail.com<br>
* **Telegram:** @vasil_12<br>
* **Skype:** Vasily Konoval (live:.cid.b78b4cef0314165b)<br>
* **Linkedin:** [Vasily Konoval](https://www.linkedin.com/in/vasily-konoval-547938206/)<br>
* **GitHub:** [Svoboda-core](https://github.com/Svoboda-core)<br>
* **Codewars:** [Svoboda-core](https://www.codewars.com/users/svoboda-core)<br>

---

### Briefly About Myself:
I am 38 years old, I started my acquaintance with programming when I was studying to be a mechanical engineer in 2001, then I became interested in programming, since then I have been tracking different areas of innovation, but it was at the level of a hobby.<br>

After graduating from the institute in 2006. and got a job as an engineer at one of the mining enterprises of our city. I began to apply my knowledge in programming for partial automation and templates, and in 2014 I became the head of the contract bureau.<br>

In 2021, I made decisions to start a new career in IT.<br>

I am sure that my previous experience and focus will help me go through this path and I will become an experienced developer, as my motto is "A difficult task is not a reason to give up, but a good chance to improve your skills".<br>

---

### Skills:
| **Python Developer**    | **Frontend Developer**      |
| :-----------: |:-----------:|
| FastAPI       | HTML5       |
| Web scraping  | CSS3        |
| Django        | SASS        |
| MySQL         | BEM         |
| PostgreSQL    | VanillaJS   |
| MongoDB       | React       |
| Docker        | Node.js     |

---

### CodeWars (Code example):

![CodeWars](https://www.codewars.com/users/svoboda-core/badges/large)

**Find the unique number KATA from CODEWARS:**
*John and Mary want to travel between a few towns A, B, C ... Mary has on a sheet of paper a list of distances between these towns. ls = [50, 55, 57, 58, 60]. John is tired of driving and he says to Mary that he doesn't want to drive more than t = 174 miles and he will visit only 3 towns.
Which distances, hence which towns, they will choose so that the sum of the distances is the biggest possible to please Mary and John?*
JavaScript:
```javascript
function chooseBestSum(t, k, arr) {
    return arr
    .reduce((r, e) => r.concat(r.filter(c => c.length < k).map(c => c.concat([e]))),[[]])
    .filter(c => c.length === k)
    .map(c => c.reduce((a, b) => a + b))
    .filter(s => s <= t)
    .sort((a, b) => b - a)[0] || null;
}
```
*Write a python function that sorts a list.The list can be string or numbers; the rest is up to you! Focus on simplicity and readability rather than efficiency.
Python:
```Python 
is_inputs_1 = ["apple", "banana", "grapes", "fat", ":)", 1, 2, 25, 5, 10, -1, -5, 0, 0.10, -0.15,[], {"user": "Vasily"}]
is_inputs_2 = [{"user": "Vasily"}, {"user": "Elen"}]

def sorted_list(inputs) -> list:
    is_namber = []
    is_str = []
    [is_namber.append(input) for input in inputs if type(input) == int or type(input) == float]
    [is_str.append(input) for input in inputs if type(input) == str]
    joinedList = [y for x in [sorted(is_namber), sorted(is_str)] for y in x]
    if len(joinedList) > 0:
        print(joinedList)
    else:
        print("List not contain str or numbers")

sorted_list(is_inputs_1)
sorted_list(is_inputs_2)
```
---

### Commercial project:
* [Travel Tool](https://github.com/svoboda-core/traveltool)
  * **Description:** Tool for formation and planning of business trips
  * **Technologies:** Django, PostgreSQL, HTML5, JS, CSS3.

---
### Expirience:
* **Diosphere Technologies (agency TestFreaks in Ukraine), Dnipro – Python Developer, May 2022 – Apr 2023**
  * Optimize and fix the program code written in Python for the correct parsing of information from sites. This information includes product data and reviews.
* **Freelance, Jan 2021 - Mar 2023**
  * Automation of various business processes using JavaScript/Python programming languages. 
* **PJSC “Central GOK” Ukraine, Kryvyi Rih - Head of Contract Bureau, Apr 2014 - Jan 2021**
  * Control over the execution of contracts. Supply planning, budget planning. Control over accounting. Analysis and updating of data in SAP ERP and Microsoft Excel. Distribution of tasks to employees and control of execution. Formation of KPIs of the department and the employee.
---

### Education:

* **Kryvyi Rih National University**
  * Transport Faculty, Department of mining equipment, 2001-2006
* **Courses:**
  * **FreeCodeCamp:**
    * [JavaScript Algorithms and Data Structures](https://freecodecamp.org/certification/Vasily_Konoval/javascript-algorithms-and-data-structures)
    * [Responsive Web Design](https://www.freecodecamp.org/certification/Vasily_Konoval/responsive-web-design)

----
### Languages:

- English \- B1 (Intermediate)
- Ukrainian \- Native
- Russian \- Native
