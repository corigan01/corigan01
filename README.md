# Hello


```c++
#include <me.hpp>
#include <vector>
#include <displayout.h>
#include <string>

int main() {
  std::vector<std::string> Programming_Languages = 
  {
  "c++", "c", "python", "type", "bash"
  };
  
  std::string Working_on = 
  "CrossSockets and Iphottub";
  
  std::vector<std::string> About = 
  {
  "I own some servers", "Starting a hosting company", "Doing a lot of c++", "Low-level web (Socket / TCP)"
  };
  
  std::string Contact = 
  "Email: Corigan01@gmail.com";
  
  // output this garbage
  displayout dis;
  
  dis.out(D_INFO, "# Programming Languages I use");
  dis.out_vec(D_INFO, &Programming_Languages); 
  
  dis.out(D_INFO, "# Working On");
  dis.out(D_INFO, Working_on);
  
  dis.out(D_INFO, "# About");
  dis.out_vec(D_INFO, &About);
  
  dis.out(D_INFO, "# Contact");
  dis.out(D_INFO, Contact);
}
```

### Output
```css
User@Ip:~$ g++ main.cpp -o about_me
User@Ip:~$ ./about_me
[INFO] # Programming Languages I use
[INFO] c++
[INFO] c
[INFO] python
[INFO] bash
[INFO] # Working On
[INFO] CrossSockets and Iphottub
[INFO] # About
[INFO] I own some servers
[INFO] Starting a hosting company
[INFO] Doing a lot of c++ 
[INFO] Low-level web (Socket / TCP)
[INFO] # Contact
[INFO] Email: Corigan01@gmail.com

User@Ip:~$ sudo reboot
```

<!--
**corigan01/corigan01** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
