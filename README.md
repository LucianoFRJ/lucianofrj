#include <iostream>
#include <cstdlib>


int main() {
    constexpr const char* bio = 
        "I am a Systems Analysis and Development student, passionate about cybersecurity career.\n"
        ""Currently studying to be a pentester\n";

    constexpr const char* subjects =
        "I am currently studying Systems Analysis and Development (ADS), focusing on:\n"
        " - Cybersecurity Professional Training (SYCP) by Solyd\n"
        " - Computer Networking fundamentals (Cisco courses)\n"
        " - Network Security and Infrastructure\n"
        " - Ethical Hacking and Cyber Defense concepts\n"
        " - Information Security and Cybersecurity practices\n";

    constexpr const char* status = 
        "[  0.000001 ] Kernel Panic - Fatal Error\n"
        "[  0.000002 ] Too many deadlines, not enough sleep.\n"
        "[  0.000003 ] System halted.\n";

    std::cout << bio << '\n' << subjects << '\n';

    std::cerr << status << std::endl;
    std::exit(EXIT_FAILURE); 

    return 0;
}
