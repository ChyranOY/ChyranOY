<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2E91E5&background=00000000&center=true&vCenter=true&width=435&lines=Hello%2C+World!;I'm+ChyranOY+(SII-Sakamoto);AI+Researcher+@+SII;Compiling+My+Life..." alt="Typing SVG" />
</div>
<div align="center">
  <i>"Dedicate to innovation in education and research in the field of AI."</i>
</div>
<br/>
```c++
#include <iostream>
#include <vector>
class AI_Researcher {
public:
    std::string name = "ChyranOY";
    std::string role = "Researcher @ Shanghai Innovation Institute";
    std::string location = "Shanghai, China";
    struct Skills {
        std::vector<std::string> languages = {"Python", "C++", "CUDA"};
        std::vector<std::string> ai_stack  = {"PyTorch", "TensorFlow", "OpenCV", "Scikit-learn"};
        std::vector<std::string> tools     = {"Docker", "Linux", "Git", "LaTeX"};
        std::vector<std::string> interest  = {"Computer Vision", "Deep Learning", "EduTech"};
    } skills;
    void say_hello() {
        std::cout << "Welcome to my repo. Let's build the future." << std::endl;
    }
};
int main() {
    AI_Researcher me;
    me.say_hello();
    return 0;
}
