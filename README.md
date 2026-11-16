# 🖥️ ALX System Engineering & DevOps

Shell scripting and web infrastructure design projects from the **ALX Software Engineering** programme.

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

## Projects

### [0x03: Shell, init files, variables and expansions](0x03-shell_variables_expansions/)

Bash one-liners that cover aliases, local and global variables, `PATH`, arithmetic expansion, number bases, brace expansion, `printf` formatting, `tr` and `awk`.

| Script | What it does |
| --- | --- |
| `0-alias` | Creates an alias (`ls` → `rm *`). ⚠️ This is a deliberate exercise, so don't source it in a real shell |
| `1-hello_you` | Prints `hello <current user>` |
| `2-path`, `3-paths` | Adds `/action` to `PATH`, and counts the directories in `PATH` |
| `4-global_variables`, `5-local_variables` | Lists environment variables, and all shell variables and functions |
| `6-…`, `7-…` | Creates a local variable, then a global (exported) variable |
| `8-` to `10-` | Arithmetic expansion: addition, division, exponents |
| `11-binary_to_decimal`, `100-decimal_to_hexadecimal` | Base conversion |
| `12-combinations` | Every two-letter combination from `aa` to `zz`, except `oo` |
| `13-print_float` | Prints a number to two decimal places |
| `101-rot13`, `102-odd`, `103-water_and_stir` | ROT13 encoding, printing odd lines, and custom-base arithmetic |

### [0x09: Web infrastructure design](0x09-web_infrastructure_design/)

Written designs, with the reasoning behind each, for hosting `www.foobar.com`:

| Task | Design |
| --- | --- |
| [0. Simple web stack](0x09-web_infrastructure_design/0-simple_web_stack/) | One server running Nginx, an application server and MySQL, with DNS explained, plus its single-point-of-failure problems |
| [1. Distributed web infrastructure](0x09-web_infrastructure_design/1-distributed_web_infrastructure/) | Three servers behind an HAProxy load balancer, and a MySQL primary–replica cluster |
| [2. Secured and monitored](0x09-web_infrastructure_design/2-secured_and_monitored_web_infrastructure/) | Firewalls, HTTPS with an SSL certificate, and monitoring clients |
| [3. Scale up](0x09-web_infrastructure_design/3-scale_up/) | A load-balancer cluster and components split onto their own servers |

## Usage

```bash
git clone https://github.com/Dwaynemaster007/alx-system_engineering-devops.git
cd alx-system_engineering-devops/0x03-shell_variables_expansions
BINARY=10100111001 ./11-binary_to_decimal     # 1337
```

Scripts that set variables (`2-path`, `6-…`, `7-…`) only affect your shell if you `source` them.

## Author

**Thubelihle Dlamini**, [GitHub](https://github.com/Dwaynemaster007) · [LinkedIn](https://linkedin.com/in/thubelihledlamini)
