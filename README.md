# Buenas, Yo soy Sebastian Pardo(UserSCP) 👋

¡Bienvenido a mi perfil de GitHub! Soy estudiante de secundaria en Confederación Suiza, me gusta aprender logica y codificar en varios lenguajes. Aquí hay un poco sobre mí:

## 💻 Tecnologías y Idiomas

### Actualmente aprendiendo:
- **Laravel**: Explorando el mundo de los frameworks PHP.
- **JavaScript**: Mejorando mis habilidades de desarrollo web.
- **Java**: Mejorando comprencion de programación orientada a objetos.
- **Python:** Explorando el análisis de datos, automatización y desarrollo web con frameworks.

### Ya dominas en:
![HTML](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/-Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat&logo=java&logoColor=white)
![C#](https://img.shields.io/badge/-C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat&logo=c%2b%2b&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

(tengo fe)

## 📚 Educación
- **Escuela secundaria**: "Confederación Suiza" Tecnica n°26 DE n°6
  
## 📈 Estadísticas de GitHub
![Tus estadísticas de GitHub](https://github-readme-stats.vercel.app/api?username=UserSCP&show_icons=true&theme=radical)

## 🌱 Proyectos y objetivos
- Construcción de aplicaciones web con Laravel.
- Creación de sitios web interactivos utilizando JavaScript.
- Desarrollo de aplicaciones robustas en Java.
- Desarrollo de pequeños proyectos en python
  
## 📫 Conéctate Conmigo
- [Email](sebastian.pardo.scp@gmail.com)
- [LinkedIn](en conversación)
--Intereses: anime(de todo), juegos(minecraft), codificar(encuentrar y manejar logica), musica(Gustavo Cerati, Spinetta,c)  
```csharp
using System;

namespace datosExtra
{
  public class Intereses
  {        
    protected string juego, codificar, deporte, pasatiempo;
    protected string[] musica;
    protected Anime anime;;
    public Intereses(Anime anime)
    {
      this.anime=anime.all();
      this.juego="Minecraft";
      this.codificar="encuentrar y manejar logica";
      this.musica = new string[] { "Gustavo Cerati", "Spinetta" , "Patricio Rey y sus Redonditos de Ricota" };  
      ///son god 
      this.deporte="futbol";
      this.pasatiempo="Tocar la guitarra";
    }
      public void MostrarInformacion()
        {
            Console.WriteLine($"Juego: {juego}");
            Console.WriteLine($"Codificar: {codificar}");
            Console.WriteLine("Música: " + string.Join(", ", musica));
            Console.WriteLine($"Deporte: {deporte}");
            Console.WriteLine($"Pasatiempo: {pasatiempo}");
            anime.All();
        }
  }
  class Programa
    {
        static void Main(string[] args)
        {
            Anime miAnime = new Anime();
            Intereses misIntereses = new Intereses(miAnime);
            misIntereses.MostrarInformacion();
        }
    }
}
¡Gracias por visitar mi perfil! Siempre estoy abierto a oportunidades de colaboración y aprendizaje.
