<div align="center">
<a href="#">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1020,50:102A43,100:00D9FF&height=220&section=header&text=Santiago%20Benavent&fontSize=58&fontColor=00D9FF&animation=fadeIn&fontAlignY=38&desc=ROBOTICS%20%7C%20EMBEDDED%20SYSTEMS%20%7C%20HARDWARE%20%7C%20SOFTWARE&descAlignY=58&descSize=16&descColor=B8F7FF" />
</a>

<br />

<a href="https://github.com/santi-bnt">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=2800&pause=900&color=00D9FF&center=true&vCenter=true&width=760&lines=%24+whoami;Robotics+%26+Intelligent+Systems+Engineering+Student;Embedded+C+%2F%2F+C%2B%2B+%2F%2F+Python;ESP32+%2B+KL25Z+%2B+Raspberry+Pi;Building+robots%2C+dashboards+and+real-time+systems;%24+make+hardware_work" alt="Typing intro" />
</a>

<br /><br />

<a href="https://github.com/santi-bnt">
  <img src="https://img.shields.io/badge/GitHub-santi--bnt-00D9FF?style=for-the-badge&labelColor=0B1020&logo=github&logoColor=white" />
</a>

<a href="https://www.linkedin.com/in/santiago-benavent-b13305330">
  <img src="https://img.shields.io/badge/LinkedIn-Santiago%20Benavent-0A66C2?style=for-the-badge&labelColor=0B1020&logo=linkedin&logoColor=white" />
</a>

<img src="https://img.shields.io/badge/STATUS-BUILDING-00D9FF?style=for-the-badge&labelColor=0B1020" />
</div>

---

```c
/* ─────────────────────────────────────────────────────────────── */
/*   ./about_me.c                                                  */
/* ─────────────────────────────────────────────────────────────── */

#include <robotics.h>
#include <embedded_systems.h>
#include <curiosity.h>

typedef struct {
    const char *name;
    const char *role;
    const char *focus[5];
    const char *stack[7];
    int         curiosity;
} engineer_t;

engineer_t me = {
    .name  = "Santiago Benavent",
    .role  = "Robotics & Intelligent Systems Engineering Student",
    .focus = {
        "Embedded Systems",
        "Robotics",
        "Hardware Integration",
        "Real-Time Dashboards",
        "Software Engineering"
    },
    .stack = {
        "C",
        "C++",
        "Python",
        "ESP32",
        "FRDM-KL25Z",
        "Raspberry Pi",
        "Firebase"
    },
    .curiosity = INT_MAX
};
```

<br />

## ⟁ &nbsp; About me

I am a Robotics and Intelligent Systems Engineering student at Tecnológico de Monterrey, focused on building systems where **software meets hardware**.

I enjoy working on embedded projects, sensor integration, robotics control, real-time dashboards, and practical software tools. My projects usually combine microcontrollers, communication protocols, web interfaces, databases, and hardware debugging.

Currently, I am strengthening my skills in **data structures, algorithms, object-oriented programming, and backend-oriented software development**.

<br />

## ⟁ &nbsp; Skills

<div align="center">
<table>
<tr>
<td valign="top" width="50%">

#### `~/languages`

<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" />
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />

#### `~/embedded`

<img src="https://img.shields.io/badge/ESP32-000000?style=for-the-badge&logo=espressif&logoColor=white" />
<img src="https://img.shields.io/badge/FRDM--KL25Z-00AEEF?style=for-the-badge&logo=nxp&logoColor=white" />
<img src="https://img.shields.io/badge/ARM-0091BD?style=for-the-badge&logo=arm&logoColor=white" />
<img src="https://img.shields.io/badge/UART-102A43?style=for-the-badge" />
<img src="https://img.shields.io/badge/I2C-102A43?style=for-the-badge" />

</td>
<td valign="top" width="50%">

#### `~/hardware`

<img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" />
<img src="https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white" />
<img src="https://img.shields.io/badge/Sensors-00D9FF?style=for-the-badge&labelColor=0B1020" />
<img src="https://img.shields.io/badge/3D%20Printing-FF6B35?style=for-the-badge" />
<img src="https://img.shields.io/badge/Circuit%20Debugging-4D96FF?style=for-the-badge" />

#### `~/tools`

<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
<img src="https://img.shields.io/badge/MCUXpresso-00AEEF?style=for-the-badge" />
<img src="https://img.shields.io/badge/PlatformIO-F5822A?style=for-the-badge&logo=platformio&logoColor=white" />

</td>
</tr>
</table>
</div>

<br />

## ⟁ &nbsp; Featured projects

<table>
<tr>
<td width="50%" valign="top">

### `SkiliAir`

Real-time air quality monitoring system using Raspberry Pi, sensors, MySQL, Flask, LCD output, alerts, and a live web dashboard.

**Tech:** Python, Flask, MySQL, Raspberry Pi, GPIO, Chart.js

</td>
<td width="50%" valign="top">

### `MATT`

Web-controlled writing robot system using Firebase, ESP32, UART communication, and an embedded KL25Z controller.

**Tech:** ESP32, Firebase, UART, C/C++, JavaScript

</td>
</tr>

<tr>
<td width="50%" valign="top">

### `KL25Z Mini Radar`

Radar-style distance scanner using ultrasonic sensing, servo movement, UART data streaming, and Python visualization.

**Tech:** FRDM-KL25Z, C, UART, Python, Matplotlib

</td>
<td width="50%" valign="top">

### `C++ OOP Projects`

Object-oriented programming projects involving classes, inheritance, polymorphism, file handling, and matrix/fraction operations.

**Tech:** C++, OOP, UML, File I/O

</td>
</tr>
</table>

<br />

## ⟁ &nbsp; Currently learning

```bash
$ studying --focus "Data Structures & Algorithms"
$ practicing --platform "LeetCode / NeetCode 150"
$ improving --topics "Big O, Hashmaps, Two Pointers, Stacks, OOP"
$ preparing --goal "Software Development Engineering interviews"
```

<br />

## ⟁ &nbsp; GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=santi-bnt&show_icons=true&theme=tokyonight&hide_border=true&title_color=00D9FF&icon_color=00D9FF" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=santi-bnt&layout=compact&theme=tokyonight&hide_border=true&title_color=00D9FF" />

</div>

<br />

## ⟁ &nbsp; Contact

<div align="center">

<a href="https://github.com/santi-bnt">
  <img src="https://img.shields.io/badge/GitHub-santi--bnt-00D9FF?style=for-the-badge&labelColor=0B1020&logo=github&logoColor=white" />
</a>

<a href="https://www.linkedin.com/in/santiago-benavent-b13305330">
  <img src="https://img.shields.io/badge/LinkedIn-Santiago%20Benavent-0A66C2?style=for-the-badge&labelColor=0B1020&logo=linkedin&logoColor=white" />
</a>

</div>

<br />

```bash
$ thanks for stopping by.
$ currently building things that move, sense, and respond.
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,50:102A43,100:0B1020&height=100&section=footer" />
