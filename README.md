# Software by Zachary Klaas

Open-source software made by Zachary Klaas with Claude, an artificial intelligence system made by Anthropic. Each program carries an open-source licence with an AI disclosure.

## Programs

### ADSR

A card game of **Attack, Decay, Sustain and Release**, played against the computer, hot-seat on one screen, or over the LAN. PyQt6; otherwise standard library only.

**Licence:** GPL-3.0-or-later · **Source:** [github.com/zklaas/adsr](https://github.com/zklaas/adsr) · **Runs on:** Linux, Windows, macOS

**AI:** Does not connect to any AI system.

<details><summary>Install on Linux at the command line (from the source code)</summary>

Type these into a **terminal** (in most file managers: right-click inside a folder > *Open in Terminal*).

```
git clone https://github.com/zklaas/adsr.git
cd adsr
python3 -m pip install --user PyQt6   # or your distribution's packages
bash install.sh
```

No git? On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `adsr-main`); open a terminal there, and skip the first two lines above.

</details>

<details><summary>Install on Windows at the command line (from the source code)</summary>

Type these into **PowerShell**: open the Start menu, type *PowerShell* and press Enter (Windows 11's *Terminal* opens PowerShell too; the Command Prompt also works). The installer needs Python first: `winget install --id Python.Python.3.13 -e --scope user`.

```
git clone https://github.com/zklaas/adsr.git
cd adsr
powershell -ExecutionPolicy Bypass -File install.ps1
```

No git? (`git` needs Git for Windows: `winget install --id Git.Git -e`) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `adsr-main`); open PowerShell there (type *powershell* in File Explorer's address bar and press Enter), and skip the first two lines above.

</details>

<details><summary>Install on macOS at the command line (from the source code)</summary>

Type these into **Terminal** (Applications > Utilities > Terminal, or press ⌘-Space and type *Terminal*). The installer needs Python first: `brew install python@3.13` (https://brew.sh), or the installer from python.org.

```
git clone https://github.com/zklaas/adsr.git
cd adsr
bash install-macos.sh
```

No git? (the first `git` command offers to install Apple's command-line tools: accept) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `adsr-main`); open Terminal there (type `cd `, drag the folder onto the Terminal window, press Return), and skip the first two lines above.

</details>

### Axelrod

Tests strategies for the **iterated prisoner's dilemma**, after Robert Axelrod's computer tournaments (1980), his ecological analysis and genetic algorithm (1984, 1987), and later work on noise. PyQt6 + Python stdlib.

**Licence:** GPL-3.0-or-later · **Source:** [github.com/zklaas/axelrod](https://github.com/zklaas/axelrod) · **Runs on:** Linux, Windows, macOS

**Download the program** (executable: double-click to install and run, nothing else needed): [Windows installer (.exe)](https://github.com/zklaas/axelrod/releases/latest/download/Axelrod-Setup-Windows.exe) · [macOS app (.dmg)](https://github.com/zklaas/axelrod/releases/latest/download/Axelrod-macOS.dmg) · [Linux app (.AppImage)](https://github.com/zklaas/axelrod/releases/latest/download/Axelrod-Linux-x86_64.AppImage)

**AI:** Does not connect to any AI system.

Or install from the source code, at the command line:

<details><summary>Install on Linux at the command line (from the source code)</summary>

Type these into a **terminal** (in most file managers: right-click inside a folder > *Open in Terminal*).

```
git clone https://github.com/zklaas/axelrod.git
cd axelrod
python3 -m pip install --user PyQt6   # or your distribution's packages
bash install.sh
```

No git? On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `axelrod-main`); open a terminal there, and skip the first two lines above.

</details>

<details><summary>Install on Windows at the command line (from the source code)</summary>

Type these into **PowerShell**: open the Start menu, type *PowerShell* and press Enter (Windows 11's *Terminal* opens PowerShell too; the Command Prompt also works). The installer needs Python first: `winget install --id Python.Python.3.13 -e --scope user`.

```
git clone https://github.com/zklaas/axelrod.git
cd axelrod
powershell -ExecutionPolicy Bypass -File install.ps1
```

No git? (`git` needs Git for Windows: `winget install --id Git.Git -e`) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `axelrod-main`); open PowerShell there (type *powershell* in File Explorer's address bar and press Enter), and skip the first two lines above.

</details>

<details><summary>Install on macOS at the command line (from the source code)</summary>

Type these into **Terminal** (Applications > Utilities > Terminal, or press ⌘-Space and type *Terminal*). The installer needs Python first: `brew install python@3.13` (https://brew.sh), or the installer from python.org.

```
git clone https://github.com/zklaas/axelrod.git
cd axelrod
bash install-macos.sh
```

No git? (the first `git` command offers to install Apple's command-line tools: accept) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `axelrod-main`); open Terminal there (type `cd `, drag the folder onto the Terminal window, press Return), and skip the first two lines above.

</details>

### BallSheet

A PyQt6 desk for Major League batter, pitcher and team numbers. Pick a team, then step through its history one season at a time.

**Licence:** GPL-3.0-or-later · **Source:** [github.com/zklaas/ballsheet](https://github.com/zklaas/ballsheet) · **Runs on:** Linux, Windows, macOS

**AI:** Does not connect to any AI system.

<details><summary>Install on Linux at the command line (from the source code)</summary>

Type these into a **terminal** (in most file managers: right-click inside a folder > *Open in Terminal*).

```
git clone https://github.com/zklaas/ballsheet.git
cd ballsheet
python3 -m pip install --user PyQt6   # or your distribution's packages
bash install.sh
```

No git? On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `ballsheet-main`); open a terminal there, and skip the first two lines above.

</details>

<details><summary>Install on Windows at the command line (from the source code)</summary>

Type these into **PowerShell**: open the Start menu, type *PowerShell* and press Enter (Windows 11's *Terminal* opens PowerShell too; the Command Prompt also works). The installer needs Python first: `winget install --id Python.Python.3.13 -e --scope user`.

```
git clone https://github.com/zklaas/ballsheet.git
cd ballsheet
powershell -ExecutionPolicy Bypass -File install.ps1
```

No git? (`git` needs Git for Windows: `winget install --id Git.Git -e`) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `ballsheet-main`); open PowerShell there (type *powershell* in File Explorer's address bar and press Enter), and skip the first two lines above.

</details>

<details><summary>Install on macOS at the command line (from the source code)</summary>

Type these into **Terminal** (Applications > Utilities > Terminal, or press ⌘-Space and type *Terminal*). The installer needs Python first: `brew install python@3.13` (https://brew.sh), or the installer from python.org.

```
git clone https://github.com/zklaas/ballsheet.git
cd ballsheet
bash install-macos.sh
```

No git? (the first `git` command offers to install Apple's command-line tools: accept) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `ballsheet-main`); open Terminal there (type `cd `, drag the folder onto the Terminal window, press Return), and skip the first two lines above.

</details>

### Boxapella

One-person multitrack video. Record yourself into one inset of a screen layout, then record again into the next inset while the earlier takes play in your headphones, and so on. All the insets play together as one master video, with every voice mixed into one soundtrack.

**Licence:** GPL-3.0-or-later · **Source:** [github.com/zklaas/boxapella](https://github.com/zklaas/boxapella) · **Runs on:** Linux, Windows, macOS

**AI:** Does not connect to any AI system.

<details><summary>Install on Linux at the command line (from the source code)</summary>

Type these into a **terminal** (in most file managers: right-click inside a folder > *Open in Terminal*).

```
git clone https://github.com/zklaas/boxapella.git
cd boxapella
python3 -m pip install --user PyQt6 imageio-ffmpeg numpy sounddevice   # or your distribution's packages
bash install.sh
```

No git? On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `boxapella-main`); open a terminal there, and skip the first two lines above.

</details>

<details><summary>Install on Windows at the command line (from the source code)</summary>

Type these into **PowerShell**: open the Start menu, type *PowerShell* and press Enter (Windows 11's *Terminal* opens PowerShell too; the Command Prompt also works). The installer needs Python first: `winget install --id Python.Python.3.13 -e --scope user`.

```
git clone https://github.com/zklaas/boxapella.git
cd boxapella
powershell -ExecutionPolicy Bypass -File install.ps1
```

No git? (`git` needs Git for Windows: `winget install --id Git.Git -e`) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `boxapella-main`); open PowerShell there (type *powershell* in File Explorer's address bar and press Enter), and skip the first two lines above.

</details>

<details><summary>Install on macOS at the command line (from the source code)</summary>

Type these into **Terminal** (Applications > Utilities > Terminal, or press ⌘-Space and type *Terminal*). The installer needs Python first: `brew install python@3.13` (https://brew.sh), or the installer from python.org.

```
git clone https://github.com/zklaas/boxapella.git
cd boxapella
bash install-macos.sh
```

No git? (the first `git` command offers to install Apple's command-line tools: accept) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `boxapella-main`); open Terminal there (type `cd `, drag the folder onto the Terminal window, press Return), and skip the first two lines above.

</details>

### Brink

A balance-of-power simulation. The world is made of **Regions** held by **Groups**, each with an amount of **Power**.

**Licence:** GPL-3.0-or-later · **Source:** [github.com/zklaas/brink](https://github.com/zklaas/brink) · **Runs on:** Linux, Windows, macOS

**AI:** Does not connect to any AI system.

<details><summary>Install on Linux at the command line (from the source code)</summary>

Type these into a **terminal** (in most file managers: right-click inside a folder > *Open in Terminal*).

```
git clone https://github.com/zklaas/brink.git
cd brink
python3 -m pip install --user PyQt6   # or your distribution's packages
bash install.sh
```

No git? On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `brink-main`); open a terminal there, and skip the first two lines above.

</details>

<details><summary>Install on Windows at the command line (from the source code)</summary>

Type these into **PowerShell**: open the Start menu, type *PowerShell* and press Enter (Windows 11's *Terminal* opens PowerShell too; the Command Prompt also works). The installer needs Python first: `winget install --id Python.Python.3.13 -e --scope user`.

```
git clone https://github.com/zklaas/brink.git
cd brink
powershell -ExecutionPolicy Bypass -File install.ps1
```

No git? (`git` needs Git for Windows: `winget install --id Git.Git -e`) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `brink-main`); open PowerShell there (type *powershell* in File Explorer's address bar and press Enter), and skip the first two lines above.

</details>

<details><summary>Install on macOS at the command line (from the source code)</summary>

Type these into **Terminal** (Applications > Utilities > Terminal, or press ⌘-Space and type *Terminal*). The installer needs Python first: `brew install python@3.13` (https://brew.sh), or the installer from python.org.

```
git clone https://github.com/zklaas/brink.git
cd brink
bash install-macos.sh
```

No git? (the first `git` command offers to install Apple's command-line tools: accept) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `brink-main`); open Terminal there (type `cd `, drag the folder onto the Terminal window, press Return), and skip the first two lines above.

</details>

### ChumpMan 11D

A hyperspace platformer: ChumpMan is stranded in an 11-dimensional space, but your screen can only ever show 3 axes ("your current 3D brane") at once. Rotate hidden dimensions into view, collect coins that only fully exist when all three of their dimensions are on screen, steer a Time axis and an Attribute axis to bend probability in your favor, and try not to run into yourself.

**Licence:** GPL-3.0-or-later · **Source:** [github.com/zklaas/chumpman11d](https://github.com/zklaas/chumpman11d) · **Play online:** [zklaas.github.io/chumpman11d](https://zklaas.github.io/chumpman11d/) · **Runs on:** Linux, Windows, macOS

**AI:** Does not connect to any AI system.

<details><summary>Install on Linux at the command line (from the source code)</summary>

Type these into a **terminal** (in most file managers: right-click inside a folder > *Open in Terminal*).

```
git clone https://github.com/zklaas/chumpman11d.git
cd chumpman11d
python3 -m pip install --user PyQt6 PyQt6-WebEngine   # or your distribution's packages
bash install.sh

# or, without installing: open game.html in a web browser (from https://github.com/zklaas/chumpman11d)
```

No git? On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `chumpman11d-main`); open a terminal there, and skip the first two lines above.

</details>

<details><summary>Install on Windows at the command line (from the source code)</summary>

Type these into **PowerShell**: open the Start menu, type *PowerShell* and press Enter (Windows 11's *Terminal* opens PowerShell too; the Command Prompt also works). The installer needs Python first: `winget install --id Python.Python.3.13 -e --scope user`.

```
git clone https://github.com/zklaas/chumpman11d.git
cd chumpman11d
powershell -ExecutionPolicy Bypass -File install.ps1

# or, without installing: open game.html in a web browser (from https://github.com/zklaas/chumpman11d)
```

No git? (`git` needs Git for Windows: `winget install --id Git.Git -e`) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `chumpman11d-main`); open PowerShell there (type *powershell* in File Explorer's address bar and press Enter), and skip the first two lines above.

</details>

<details><summary>Install on macOS at the command line (from the source code)</summary>

Type these into **Terminal** (Applications > Utilities > Terminal, or press ⌘-Space and type *Terminal*). The installer needs Python first: `brew install python@3.13` (https://brew.sh), or the installer from python.org.

```
git clone https://github.com/zklaas/chumpman11d.git
cd chumpman11d
bash install-macos.sh

# or, without installing: open game.html in a web browser (from https://github.com/zklaas/chumpman11d)
```

No git? (the first `git` command offers to install Apple's command-line tools: accept) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `chumpman11d-main`); open Terminal there (type `cd `, drag the folder onto the Terminal window, press Return), and skip the first two lines above.

</details>

### Classifier

Sorts your software into **Development Groups**, decides which of it is **Cleared** for an open-source licence, writes that licence (with an AI disclosure naming Claude), records which operating systems each one supports, and keeps GitHub in line.

**Licence:** GPL-3.0-or-later · **Source:** [github.com/zklaas/classifier](https://github.com/zklaas/classifier) · **Runs on:** Linux

**AI:** Runs without AI; an optional part connects to Claude.

<details><summary>Install on Linux at the command line (from the source code)</summary>

Type these into a **terminal** (in most file managers: right-click inside a folder > *Open in Terminal*).

```
git clone https://github.com/zklaas/classifier.git
cd classifier
python3 -m pip install --user PyQt6 PyQt6-WebEngine   # or your distribution's packages
bash install.sh
```

No git? On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `classifier-main`); open a terminal there, and skip the first two lines above.

</details>

### Quizboard

A 6 × 6 board of point values, questions and answers, read from an Excel workbook. Six column topics run across the top; under each topic, six tiles show their points, 1 to 6 going down.

**Licence:** GPL-3.0-or-later · **Source:** [github.com/zklaas/quizboard](https://github.com/zklaas/quizboard) · **Runs on:** Linux, Windows, macOS

**AI:** Does not connect to any AI system.

<details><summary>Install on Linux at the command line (from the source code)</summary>

Type these into a **terminal** (in most file managers: right-click inside a folder > *Open in Terminal*).

```
git clone https://github.com/zklaas/quizboard.git
cd quizboard
python3 -m pip install --user PyQt6   # or your distribution's packages
python3 quizboard.py
```

No git? On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `quizboard-main`); open a terminal there, and skip the first two lines above.

</details>

<details><summary>Install on Windows at the command line (from the source code)</summary>

Type these into **PowerShell**: open the Start menu, type *PowerShell* and press Enter (Windows 11's *Terminal* opens PowerShell too; the Command Prompt also works). The installer needs Python first: `winget install --id Python.Python.3.13 -e --scope user`.

```
git clone https://github.com/zklaas/quizboard.git
cd quizboard
powershell -ExecutionPolicy Bypass -File install.ps1
```

No git? (`git` needs Git for Windows: `winget install --id Git.Git -e`) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `quizboard-main`); open PowerShell there (type *powershell* in File Explorer's address bar and press Enter), and skip the first two lines above.

</details>

<details><summary>Install on macOS at the command line (from the source code)</summary>

Type these into **Terminal** (Applications > Utilities > Terminal, or press ⌘-Space and type *Terminal*). The installer needs Python first: `brew install python@3.13` (https://brew.sh), or the installer from python.org.

```
git clone https://github.com/zklaas/quizboard.git
cd quizboard
bash install-macos.sh
```

No git? (the first `git` command offers to install Apple's command-line tools: accept) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `quizboard-main`); open Terminal there (type `cd `, drag the folder onto the Terminal window, press Return), and skip the first two lines above.

</details>

### VocalFry

Reshape a voice recording across the range of human voices: pitch, vocal-tract length (formants), voice quality and timing, each on a slider + numeric field.

**Licence:** GPL-3.0-or-later · **Source:** [github.com/zklaas/vocalfry](https://github.com/zklaas/vocalfry) · **Runs on:** Linux, Windows, macOS

**AI:** Does not connect to any AI system.

<details><summary>Install on Linux at the command line (from the source code)</summary>

Type these into a **terminal** (in most file managers: right-click inside a folder > *Open in Terminal*).

```
git clone https://github.com/zklaas/vocalfry.git
cd vocalfry
python3 -m pip install --user PyQt6 imageio-ffmpeg numpy pyworld sounddevice   # or your distribution's packages
bash install.sh
```

No git? On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `vocalfry-main`); open a terminal there, and skip the first two lines above.

</details>

<details><summary>Install on Windows at the command line (from the source code)</summary>

Type these into **PowerShell**: open the Start menu, type *PowerShell* and press Enter (Windows 11's *Terminal* opens PowerShell too; the Command Prompt also works). The installer needs Python first: `winget install --id Python.Python.3.13 -e --scope user`.

```
git clone https://github.com/zklaas/vocalfry.git
cd vocalfry
powershell -ExecutionPolicy Bypass -File install.ps1
```

No git? (`git` needs Git for Windows: `winget install --id Git.Git -e`) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `vocalfry-main`); open PowerShell there (type *powershell* in File Explorer's address bar and press Enter), and skip the first two lines above.

</details>

<details><summary>Install on macOS at the command line (from the source code)</summary>

Type these into **Terminal** (Applications > Utilities > Terminal, or press ⌘-Space and type *Terminal*). The installer needs Python first: `brew install python@3.13` (https://brew.sh), or the installer from python.org.

```
git clone https://github.com/zklaas/vocalfry.git
cd vocalfry
bash install-macos.sh
```

No git? (the first `git` command offers to install Apple's command-line tools: accept) On the GitHub page click **Code > Download ZIP** and unpack it (the folder is called `vocalfry-main`); open Terminal there (type `cd `, drag the folder onto the Terminal window, press Return), and skip the first two lines above.

</details>

---

If something doesn't work, please write to zklaastest-testing@yahoo.com.

*This page is generated by Classifier from each program's Development Group, licence and platform tracks.*
