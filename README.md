<!-- Encabezado Central -->
<h1 align="center"><b>Hola, Soy Luis Francisco </b><img src="assets/mdImages/handshake.gif" width="55"></h1>

<!-- Imagen de escritura animada en el centro -->
<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Time+New+Roman&color=cyan&size=35&center=true&vCenter=true&width=600&height=100&lines=Estudiante+de+la+BUAP;Tecnico+del+CECyTE;Futuro+programador;Amante+del+lenguaje+python+y+C"></a>
</p>

<!-- Sección 'Sobre mí' -->
## <picture><img src = "assets/mdImages/about_me.gif" width = 50px></picture> **Sobre mí**

- Un apasionado desarrollador autodidacta.
- Actualmente aprendiendo Desarrollo Web por mi cuenta.
- Sitio web personal [enlace](https://t4dokiary.github.io/about/).
- Actualmente disponible para una pasantía o una nueva oportunidad laboral, para aprender y crecer en el campo de la tecnología.

``` python
class T4dokiary:
    def __init__(self):
        self.name = "Luis Francisco"
        self.username = "t4dokiary"
        self.location = "Tlaxcala, México"
        self.web = "https://t4dokiary.github.io/about/"
        self.email = {"gmail": "luis.matlalcuatzi@gmail.com",
                      "hotmail": "luis.matlalcuatzi@hotmail.com"}
        self.redes_sociales = {"linkedin": "https://www.linkedin.com/in/luis-francisco-matlalcuatzi-gonzalez/", 
                               "twitter": "https://twitter.com/TadokiaryKazuto", 
                               "facebook": "https://www.facebook.com/whiichito", 
                               "instagram": "https://www.instagram.com/wichito_fmg/"}

    def __str__(self):
        redes_sociales_str = "\n".join([f"{red}: {url}" for red, url in self.redes_sociales.items()])
        return (f"Nombre: {self.name}\n"
                f"Ubicación: {self.location}\n"
                f"Web: {self.web}\n"
                f"Contacto Gmail: {self.email['gmail']}\n"
                f"Contacto Hotmail: {self.email['hotmail']}\n"
                + redes_sociales_str)

if __name__ == '__main__':
    me = T4dokiary()
    print(me)

```



<!-- Sección 'Habilidades' -->
## <img src="assets/mdImages/coding.webp" width ="35"><b> Habilidades</b>

<p align="center">

- **Lenguajes**:
    
    ![C](https://img.shields.io/badge/C%20-%232370ED.svg?style=for-the-badge&logo=c&logoColor=white)
    ![C++](https://img.shields.io/badge/C++%20-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
    ![Python](https://img.shields.io/badge/Python%20-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)

- **Desarrollo Front-End**:

   ![HTML5](https://img.shields.io/badge/HTML5%20-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
   ![CSS3](https://img.shields.io/badge/CSS%20-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
   ![JavaScript](https://img.shields.io/badge/JavaScript%20-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

- **Alojamiento en la Nube**:

    ![Github Pages](https://img.shields.io/badge/GitHub%20Pages-%23327FC7.svg?style=for-the-badge&logo=github&logoColor=white)
    
- **Software y Herramientas**:

    ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
    ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
    ![Google](https://img.shields.io/badge/google-%234285F4.svg?style=for-the-badge&logo=google&logoColor=white)
    ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
    ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) 

- **Extras**:

    ![Terminal](https://img.shields.io/badge/Terminal-%23054020?style=for-the-badge&logo=gnu-bash&logoColor=white)
    ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)

