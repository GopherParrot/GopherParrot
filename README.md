# <p align="center">Hi! <img src="https://raw.githubusercontent.com/light-hat/light-hat/refs/heads/main/assets/hello.gif" width="30" height="30"> I'm Willie Parrot <img src="https://c.tenor.com/x-kqDAmw2NQAAAAM/parrot-party.gif" width="30" height="40"></p>
<p align="center">Hi again! I really like coding
<img src="https://media1.tenor.com/m/JIS_KDKKsgYAAAAd/guaton-computadora.gif" width="70" height="70"></p>
<hr>

<!--  === ABOUT ME === -->
## <p align="center">About Me<img src="https://media1.tenor.com/images/2d76769affec50319ae14cdd3cfd21ec/tenor.gif?itemid=15053329" width="40" height="40"></p>

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
  Info: Info{Name: "Willie Parrot", Age: 21, IsStudent: true}, // Um actually I'm 13 ☝🤓
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

You don't know the output? Let me help you :)<br>
Output:
```
My name is Willie Parrot
I am 21 years old
Am I a student? yes
My hobbies are Origami (折り紙), Kirigami (切り紙) and Kumiko (組子), and I'm not Japanese
```

## <p align="center">Skills and Tech Stack <img src="https://media1.tenor.com/images/2d76769affec50319ae14cdd3cfd21ec/tenor.gif?itemid=15053329" width="40" height="40"></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=go,python,javascript,html,css,typescript,react,mysql,nodejs,django,vscode,github,git,docker,googlecloud,arduino,c,cpp,java,cs,firebase,flutter,gitlab,godot,neovim,raspberrypi,stackoverflow,gmail,eclipse,&perline=8&theme=dark" alt="My Skills">
</p>

## <p align="center">My GitHub Stats <img src="https://media1.tenor.com/images/2d76769affec50319ae14cdd3cfd21ec/tenor.gif?itemid=15053329" width="40" height="40"></p>

## <p align="center">![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=GopherParrot&theme=dark&hide_border=true)</p>

## <p align="center">![GopherParrot's GitHub Stats](https://github-readme-stats.vercel.app/api?username=GopherParrot&show_icons=true&theme=tokyonight&hide_rank=true&count_private=true&custom_title=My%20Code%20Journey)</p>


## <p align="center">My GitHub Stats & Activity <img src="https://media1.tenor.com/images/2d76769affec50319ae14cdd3cfd21ec/tenor.gif?itemid=15053329" width="40" height="40"></p>

![GitHub Contribution Snake](https://github.com/GopherParrot/GopherParrot/blob/output/dist/github-contribution-grid-snake.svg)

<p align="center">
  ![Wakatime Stats](https://github.com/GopherParrot/GopherParrot/blob/main/metrics/wakatime.svg)
</p>

<p align="center">
  ![Profile Views](https://views.whatilearn.today/views/github/GopherParrot/README.md)
</p>
<!--## <p align="center">![Most Used Repos](https://github-readme-stats.vercel.app/api/pin/?username=GopherParrot&repo=YOUR_POPULAR_REPO_1&theme=tokyonight)</p>
## <p align="center">![Most Used Repos](https://github-readme-stats.vercel.app/api/pin/?username=GopherParrot&repo=YOUR_POPULAR_REPO_2&theme=tokyonight)</p>-->
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
