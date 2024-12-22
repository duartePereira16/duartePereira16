# About Me

```java
public class Profile {
    
    private String name = "Duarte Pereira";
    private String bio = "Computer Science Student at NOVA FCT";
    private int age = 19;
    private String location = "Portugal";

    private String[] favoriteLanguages = {"Java", "Python", "C"};
    private String[] interests = {"Cryptography", "Machine Learning", "Cloud computing"};


    public void introduce() {
        System.out.println("Hello, world! I'm " + name + ".");
        System.out.println("I enjoy coding, solving problems, and learning new things.");
    }

    public void showcaseSkills() {
        System.out.println("Here are some of my favorite languages:");
        for (String language : favoriteLanguages) {
            System.out.println("- " + language);
        }
    }

    public void displayInterests() {
        System.out.println("I'm interested in:");
        for (String goal : learningGoals) {
            System.out.println("- " + goal);
        }
    }

    public static void main(String[] args) {
        Profile profile = new Profile();
        profile.introduce();
        profile.showcaseSkills();
        profile.displayGoals();
    }
}
```
<!---
duartePereira16/duartePereira16 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
