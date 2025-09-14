<h1 align="center">Hi, I'm 4zbov 👋</h1>

### 👤 Bio
- 🔭 I'm currently working on cool personal projects.
- 🌱 I’m learning about AI, backend dev, and automation.
- 💬 Ask me about Python, JavaScript, or anything tech.
- 📫 Contact me: yourname@example.com
- 🧠 Fun fact: I love building tools that automate boring stuff.

---

### 🚀 Skills

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=for-the-badge&logo=css3)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

---

### 📜 Code Showcase

```python
# Simple username generator (no digits)
import random
import string

def gen():
    letters = string.ascii_lowercase
    return ''.join(random.choice(letters) for _ in range(4))

number = 100
usernames = [gen() for _ in range(number)]

with open("users.txt", "w") as users_file:
    for username in usernames:
        users_file.write(f"{username}\n")
