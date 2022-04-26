# **PALINDROMIC WORDS**

# Information

* **If a word gives the same word when read backwards, that word is "Palindromic Word".**

# Technologies Used

* **JAVA**

# Contents

* It returns true and false with a boolean variable, indicating whether the typed word is true or false.

* With the if condition in the while and for loop, the program will run fine.

<br />

# Codes

```Java

        public class PalindromicWords{

            static boolean isPalindrome(String str){

                int i = 0, j = str.length() - 1;

                while(i < j){

                    if(str.charAt(i) != str.charAt(j))

                        return false;

                    i++;

                    j--;

                }

                return true;

            }


```

```Java

            static boolean isPalindrome2(String str){

                String reverse = "";

                for(int i = str.length() - 1; i >= 0; i--){

                    reverse += str.charAt(i);

                }

                if(str.equals(reverse))

                    return true;

                else

                    return false;

            }

            public static void main(String[] args){

                System.out.println(isPalindrome("level"));

            }
        }

```

```bash

    true

```

<br />

# LINK

* Click here https://github.com/Fogo9/PalindromicWords.git to access the Github page for this project.

<br />

# LICENSE

* This software is licensed By Tuncay Demir under the MIT license.

<br />

>[Patika.dev](https://app.patika.dev/fogomurphy)

<br/>

| Name |  Email |
| ---- |  ----- |
| Tuncay | tuncaydemir682@gmail.com |
