import sys
import time

def main():
    banner = (
        "============================================\n"
        "   system boot sequence initialized\n"
        "============================================\n\n"
    )

  profile = (
        "[ user ]       lucianofrj\n"
        "[ role ]       Software Developer / Student\n"
        "[ focus ]      Systems, Backend, Security\n"
        "[ environment ]Linux | Git | VS Code\n\n"
    )

   expertise = (
        "Loaded competencies:\n"
        " - Programming Logic & Algorithms\n"
        " - Data Structures\n"
        " - Object-Oriented Programming\n"
        " - Version Control (Git / GitHub)\n"
        " - Linux Command Line\n"
        " - Software Development Fundamentals\n\n"
    )

  system_log = [
        "[ 0.000031 ] initializing runtime environment",
        "[ 0.000114 ] loading core modules",
        "[ 0.000287 ] validating system state",
        "[ 0.000512 ] all services operational",
        "[ 0.000768 ] system ready\n"
    ]

  sys.stdout.write(banner)
    sys.stdout.write(profile)
    sys.stdout.write(expertise)

  for line in system_log:
        sys.stderr.write(line + "\n")
        time.sleep(0.15)

  sys.exit(0)


if __name__ == "__main__":
    main()
