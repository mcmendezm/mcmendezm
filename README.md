# Generating the readMe.md content with the required structure

readme_content = """
<h1 align="center"> Hi 👋, I'm Maria Camila Mendez </h1>
<h2 align="center"> Frontend Developer </h2>

[![](https://img.shields.io/badge/mcmendezm-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mcmendezm)
[![](https://img.shields.io/badge/mcmendezm-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mcmendezm/)

- 🔬 I have 2 years of experience developing web applications, combining my technical and analytical skills to solve complex problems.

- 💻 I enjoy designing and building web interfaces using technologies like HTML, CSS, JavaScript, React, and Next.js with a focus on user experience (UX/UI).

- 📫 How to reach me: <a href="mailto:mcmendezmanotas@gmail.com">mcmendezmanotas@gmail.com</a>

- 🔭 I’m currently working on **frontend development at Inference, optimizing ecommerce platforms.**

## 𝗖𝘂𝗿𝗿𝗲𝗻𝘁𝗹𝘆 𝘄𝗼𝗿𝗸𝗶𝗻𝗴 𝗼𝗻
<section align="center">

<a href="https://niver-nieq.github.io/team-project/"><img src="https://github.com/mcmendezm/mcmendezm/blob/main/image/icecream.png" alt="IceCream Landing Page" width="600" /></a>


<a href="https://mcmendezm.github.io/FundacionAntivirus/"><img src="https://github.com/mcmendezm/mcmendezm/blob/main/image/antivirus.png" alt="Fundación Antivirus" width="600" /></a>


<a href="https://mcmendezm.github.io/E-commerce/"><img src="https://github.com/mcmendezm/mcmendezm/blob/main/image/shope.png" alt="Shope" width="600" /></a>


<a href="https://mcmendezm.github.io/Movies/"><img src="https://github.com/mcmendezm/mcmendezm/blob/main/image/appMovies.png" alt="Movies app" width="600" /></a>


</section>

## Github Stats
<section align="center">
  
![GitHub Stats](https://github-readme-streak-stats.herokuapp.com/?user=mcmendezm&theme=tokyonight&hide_border=false)

</section>

## Project Previews
### 1. IceCream Landing Page  
<a href="https://niver-nieq.github.io/team-project/"><img src="https://user-images.githubusercontent.com/70703371/121320996-ef0e7e80-c8c2-11eb-914d-31da7ba238c2.png" alt="IceCream Landing Page" width="600" /></a>  

---

### 2. Fundación Antivirus  
<a href="https://mcmendezm.github.io/FundacionAntivirus/"><img src="https://user-images.githubusercontent.com/70703371/121321645-7f4c7f00-c8c3-11eb-8d0b-38092968d0ec.png" alt="Fundación Antivirus" width="600" /></a>  

---

### 3. Shope Ecommerce  
<a href="https://mcmendezm.github.io/E-commerce/"><img src="https://user-images.githubusercontent.com/70703371/121321982-dc483500-c8c3-11eb-9304-f9b287d26c91.png" alt="Shope Ecommerce" width="600" /></a>  

---

### 4. App Movies  
<a href="https://mcmendezm.github.io/Movies/"><img src="https://user-images.githubusercontent.com/70703371/121322328-377a2780-c8c4-11eb-8e4d-83b7a77e262f.png" alt="App Movies" width="600" /></a>  

---

## Tech Stack

![Git](https://img.shields.io/badge/-Git-%23F05032?style=for-the-badge&logo=git&logoColor=%23ffffff)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

---

"""

# Write this to a readMe.md file
with open('/mnt/data/readMe.md', 'w') as file:
    file.write(readme_content)

"/mnt/data/readMe.md"
