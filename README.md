<h2>Hi, <strong>I'm Vargas Diego!</strong><img src="https://i.gifer.com/GBNo.gif" alt="chimuelo" width="30"></h2>
<img align='right' src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" alt="programmer" width="220" height="200">        

<p><em>I graduated as a full stack developer in <a href="https://4geeks.com/"> 4Geeks Academy</a><img src="https://media.giphy.com/media/ZGesfySTrBOrPd4OxX/giphy.gif" alt="graduation" width="50"></em></p>
 
[![Linkedin: diego-vargas33](https://img.shields.io/badge/Linkedin-diego--vargas33-blue?style=plastic&logo=linkedin&logoColor=white&colorA=black)](https://www.linkedin.com/in/diego-vargas33/)
### <img src="https://media.giphy.com/media/AcQBDzT3hvA1dZFGG4/giphy.gif" alt="evolution gastly" width="50"> something more about me...
<br>

```java
public class DeveloperProfileVd {

    // Atributos
    private String pronouns = "he/him";
    private String[] languages = {"Java", "JavaScript", "Python", "HTML", "CSS"};
    private String[] frameworks = {"React", "Flask", "Node.js", "Hibernate", "JUnit"};
    private String[] architectures = {"APIs", "Singleton", "MVC"};
    private String challenge = "Currently working on mastering Java and Spring Boot!";

    // Método para mostrar la información
    public void showProfile() {
        System.out.println("Pronouns: " + pronouns);
        System.out.println("Languages: " + String.join(", ", languages));
        System.out.println("Frameworks: " + String.join(", ", frameworks));
        System.out.println("Architectures: " + String.join(", ", architectures));
        System.out.println("Current Challenge: " + challenge);
    }

    // Métodos para describir hobbies
    public void showHobbies() {
        System.out.println("In my free time, I enjoy:");
        playPadel();
        codePersonalProjects();
        playVideoGames();
    }

    private void playPadel() {
        System.out.println("- I play padel with friends and I play tournaments to test my level.");
    }

    private void codePersonalProjects() {
        System.out.println("- Working on personal coding projects.");
    }

    private void playVideoGames() {
        System.out.println("- Playing video games, strategy games.");
    }

    public static void main(String[] args) {
        DeveloperProfileVd devProfile = new DeveloperProfileVd();
        devProfile.showProfile();
        devProfile.showHobbies();
    }
}
```
-----

