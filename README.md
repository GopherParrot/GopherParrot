# <p align="center">Hi! <img src="https://raw.githubusercontent.com/light-hat/light-hat/refs/heads/main/assets/hello.gif" width="30" height="30"> I'm Willie Parrot <img src="https://c.tenor.com/x-kqDAmw2NQAAAAM/parrot-party.gif" width="30" height="40"></p>
<p align="center">Hi again! I really like coding
<img src="https://media1.tenor.com/m/JIS_KDKKsgYAAAAd/guaton-computadora.gif" width="70" height="70"></p>
<hr>

<!--  === ABOUT ME === -->
## <p align="center">About Me <img src="https://media1.tenor.com/images/2d76769affec50319ae14cdd3cfd21ec/tenor.gif?itemid=15053329" width="40" height="40"></p>

```go
package main

import "fmt"

type Info struct {
  Name string
  Age int
  IsStudent bool
}

type InfoAboutMe struct {
  Info
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

You don't know the output? Let me help you :)  
Output:
```
My name is Willie Parrot
I am 21 years old
Am I a student? yes
My hobbies are Origami (折り紙), Kirigami (切り紙) and Kumiko (組子), and I'm not Japanese
```

## <p align="center">Skills and Tech Stack</p>
### <img src="https://media1.tenor.com/images/2d76769affec50319ae14cdd3cfd21ec/tenor.gif?itemid=15053329" width="40" height="40"> Languages:
<img src="https://media.tenor.com/TCMWkxIkF9IAAAAi/dancing-gopher.gif" width="70" height="70"> <!-- Golang -->
<img src="https://avatars.githubusercontent.com/u/25699522?s=280&v=4" width="70" height="70"> <!-- C -->
<img src="https://fileviewerplus.com/img/icon/256/cpp-68.png" width="70" height="70"> <!-- C++ -->
<img src="https://camo.githubusercontent.com/a8c24c0c69005509721bcfa06b7818b2a732447e11f1a36c8cbda6937e533cd3/68747470733a2f2f74656368737461636b2d67656e657261746f722e76657263656c2e6170702f6a6176612d69636f6e2e737667" width="70" height="70"> <!-- Java -->
<img src="https://w7.pngwing.com/pngs/51/656/png-transparent-c-hd-logo.png" width="70" height="70"> <!-- C# -->
<img src="https://brandslogos.com/wp-content/uploads/images/large/python-logo.png" width="70" height="70"> <!-- Python -->
<img src="https://th.bing.com/th/id/R.6c8f0a0e377cfa70efcd35ff52893b17?rik=iqhl8JD0f9LLpA&pid=ImgRaw&r=0" width="70" height="70"> <!-- HTML -->
<img src="https://logospng.org/download/css-3/logo-css-3-2048.png" width="70" height="70"> <!-- CSS -->
<img src="https://th.bing.com/th/id/R.04c5f18749c6a1c64b65f6d8f26d7b53?rik=LkrYgbJM3QA11g&riu=http%3a%2f%2fpluspng.com%2fimg-png%2fjavascript-vector-png-javascript-vector-logo-600.png&ehk=AXgaWQyvJOW74V%2fR1QuC2sk1YLpGBMJiGQVzBM07y2Q%3d&risl=&pid=ImgRaw&r=0" width="70" height="70"> <!-- JavaScript -->

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
