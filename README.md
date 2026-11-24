<div align="center">

  <!-- Top Dynamic Wave Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1F6FEB,100:58A6FF&height=120&section=header" width="100%" alt="Header Wave" />

  <!-- Animated Name Switcher: TomLifey <-> Mostafa Khalid -->
  <a href="https://github.com/TomLifey">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=36&duration=2400&pause=1200&color=58A6FF&center=true&vCenter=true&width=500&height=60&lines=TomLifey;Mostafa+Khalid" alt="TomLifey | Mostafa Khalid" />
  </a>

  <br/>

  <!-- Animated Terminal Tagline -->
  <a href="https://github.com/TomLifey">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&duration=2800&pause=1000&color=3FB950&center=true&vCenter=true&width=580&height=35&lines=%3E_+Software+Engineering+%26+42+Core+Student;%3E_+Low-Level+C%2FC%2B%2B+%7C+Python+%7C+Linux+Systems;%3E_+Building+Software+From+First+Principles" alt="Terminal Tagline" />
  </a>

  <br/>

  <!-- Live Profile View Counter -->
  <img src="https://komarev.com/ghpvc/?username=TomLifey&label=PROFILE+VIEWS&color=1F6FEB&style=for-the-badge" alt="Profile Views" />

  <br/><br/>

  <!-- Vertically Stacked Identity & Network Badges -->
  <a href="https://www.linkedin.com/in/mostfakhaled/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Mostafa_Khalid-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn: Mostafa Khalid" />
  </a>
  <br/>
  <a href="https://discord.com/users" target="_blank">
    <img src="https://img.shields.io/badge/Discord-TomLifey-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord: TomLifey" />
  </a>
  <br/>
  <a href="https://profile.intra.42.fr/users/mabutair" target="_blank">
    <img src="https://img.shields.io/badge/42_Intra-mabutair-161B22?style=for-the-badge&logo=42&logoColor=white" alt="42 Intra: mabutair" />
  </a>

</div>

<br/>

---

### `>_ whoami`

```c
#include <stdbool.h>

typedef struct s_engineer
{
	char	*name;
	char	*handle;
	char	*intra;
	char	*discord;
	char	*os;
	char	*toolchain;
	char	*focus[3];
	bool	first_principles;
}	t_engineer;

int	main(void)
{
	t_engineer	tommy = {
		.name             = "Mostafa Khalid",
		.handle           = "TomLifey",
		.intra            = "mabutair",
		.discord          = "TomLifey",
		.os               = "Arch Linux / Linux Mint (XFCE)",
		.toolchain        = "Neovim + gcc/g++ + Make + Norminette",
		.focus            = {"Systems Programming", "Algorithms", "Data & AI"},
		.first_principles = true
	};
	return (0);
}
