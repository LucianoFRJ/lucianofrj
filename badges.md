<h1 align="center">👨‍💻 Cybersecurity Student</h1>

<p align="center">
  <img src="https://media.giphy.com/media/26ufdipQqU2lhNA4g/giphy.gif" width="400">
</p>

---

## 🧠 About Me

```cpp
#include <iostream>
#include <cstdlib>

int main() {
    constexpr const char* bio = 
        "I am a Systems Analysis and Development student, passionate about cybersecurity.\n"
        "Currently studying to become a Pentester.\n";

    constexpr const char* subjects =
        "Currently focused on:\n"
        " - Cybersecurity Professional Training (SYCP) by Solyd\n"
        " - Computer Networking (Cisco courses)\n"
        " - Network Security and Infrastructure\n"
        " - Ethical Hacking and Cyber Defense\n"
        " - Information Security practices\n";

    constexpr const char* status = 
        "[  0.000001 ] Kernel Panic - Fatal Error\n"
        "[  0.000002 ] Too many deadlines, not enough sleep.\n"
        "[  0.000003 ] System halted.\n";

    std::cout << bio << '\n' << subjects << '\n';
    std::cerr << status << std::endl;

    std::exit(EXIT_FAILURE);
    return 0;
}
