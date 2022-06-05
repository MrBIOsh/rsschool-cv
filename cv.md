![Photo](/Photo_CV.jpg)
# Pavel Komysov
## Frontend Developer
=============================
#### E-mail: komysovpv@gmail.com
#### Discord: Pavel Komysov (@MrBIOsh)
=============================
### My Projects
------------------------------
- [Healthy food shop](https://mrbiosh.github.io/Module02-Shop/dist/)
- [Online - GYM site](https://mrbiosh.github.io/Module01_Diplom/index.html)
- [Burger shop](https://mrbiosh.github.io/Module01_Burger/index.html)
- [Portfolio](https://mrbiosh.github.io/Module02-Diplom/dist/)

### About
------------------------------
I'm a beginner Frontend-Developer. My goal is to become a first-class specialist in this field. I enjoy learning new technologies and try to put them into practice. Strive to be a successful developer.

> "Тake a step and the road will appear by itself" - Steve Jobs.

### Skills
------------------------------
* HTML
* CSS
* SASS/SCSS
* JS
* Webpack
* Git
* Java Core
* BEM
* Visual Studio Code

### Examples code from CodeWars 
------------------------------
[CodeWars](https://www.codewars.com/users/BIOsh/completed_solutions)
1. Disemvowel Trolls
    - _Description:_
    Trolls are attacking your comment section!
    A common way to deal with this situation is to remove all of the vowels from the trolls' comments, neutralizing the threat.
    Your task is to write a function that takes a string and return a new string with all vowels removed.
    For example, the string "This website is for losers LOL!" would become "Ths wbst s fr lsrs LL!".
    - _*Solution:*_
    ```
    public class Troll {
    public static String disemvowel(String str) {
        // Code away...
      return str.replaceAll("[aeiouAEIOU]", "");
    }
}
    ```
    
2. Find the smallest integer in the array
    - _Description:_
    Given an array of integers your solution should find the smallest integer.

    For example:

    Given [34, 15, 88, 2] your solution will return 2
    Given [34, -345, -1, 100] your solution will return -345
    You can assume, for the purpose of this kata, that the supplied array will not be empty.
    - _*Solution:*_
    ```
    public class SmallestIntegerFinder {
        public static int findSmallestInt(int[] args) {
        
            for (int i = args.length - 1; i > 0; i--) {        
                
                for (int j = 0; j < i; j++) {          
                if (args[j] > args[j+1]) {
                    
                    int tmp = args[j];
                    args[j] = args[j+1];
                    args[j+1] = tmp;
                    
                    }            
                }            
            }        
        return args[0];
        }
    }
    ```

### Education
------------------------------
* Far Eastern Federal University, Vladivostok
    - Infocommunication technologies and communication systems
    - Android Developer

### Courses
------------------------------
* Web Developer on the [AnnBlok](https://annblok.ru/)

### Languages
------------------------------
* Russian - Native
* English - intermediate (B1)

### Hobbies
------------------------------
* Chess
* Volleyball
* Electronics