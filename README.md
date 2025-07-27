# <p align="center">Hi! <img src="https://raw.githubusercontent.com/light-hat/light-hat/refs/heads/main/assets/hello.gif" width="30" height="30"> I'm Willie Parrot <img src="https://c.tenor.com/x-kqDAmw2NQAAAAM/parrot-party.gif" width="30" height="40"></p>
<p align="center">Hi again! I really like coding <img src="https://media1.tenor.com/m/JIS_KDKKsgYAAAAd/guaton-computadora.gif" width="40" height="40"></p>  
<hr>
## <p align="center"><img src="https://media1.tenor.com/images/2d76769affec50319ae14cdd3cfd21ec/tenor.gif?itemid=15053329" width="40" height="40"> About Me</p>  
```
package main

import "fmt"

type Info struct {
  Name string
  Age int
  IsStudent bool
}

type InfoAboutMe struct {
  Person
  Hobby string
}

var introduce = InfoAboutMe{
  Person: Info{Name: "Willie Parrot", Age: 21, IsStudent: true}, // Um actually I'm 13 ☝🤓
  Hobby: "Origami (折り紙), Kirigami (切り紙) and Kumiko (組子), and I'm not Japanese",
}
 
func main() {
  amIaStudent := "no"
  if introduce.IsStudent {
    amIaStudent = "yes"
  }
  fmt.Println("My name is ", introduce.Name)
  fmt.Println("I am ", introduce.Age, " years old")
  fmt.Println("Am I a student? ", amIaStudent)
  fmt.Println("My hobbies are ", introduce.Hobby)
}
```
<!-- 
**GopherParrot/GopherParrot** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
