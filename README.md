<div align="center">

  <h1 align="center">Hey there, I'm <a href="https://timo.seyfarth.dev" target="_blank">Timo</a>! <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="35px"></h1>

  <p>
    <b>Full-Stack Developer based in Germany <img src="https://upload.wikimedia.org/wikipedia/commons/f/f6/Animated-Flag-Germany.gif" width="25px"></b><br>
  </p>

  <a href="#-tech-stack"><strong>Tech Stack below »</strong></a>
  <br />
</div>

### 📦 Milestone Projects

<table width="100%">
  <tr>
    <td colspan="3" align="center" bgcolor="#151515">
      <font size="5">🏛️ <b>Published Libraries</b></font>
    </td>
  </tr>
  <tr>
    <td width="33.3%" align="center" valign="top">
      <br>
      <a href="https://github.com/timoseyfarth/tabler-icons-kmp" target="_blank"><b>⏺️ Tabler Icons KMP</b></a>
      <p>~6,000 high-quality icons ready for Jetpack Compose & KMP.</p>
      <a href="https://central.sonatype.com/artifact/dev.seyfarth/tabler-icons-kmp" target="_blank">
        <img src="https://img.shields.io/maven-central/v/dev.seyfarth/tabler-icons-kmp" alt="Tabler Icons KMP Version">
      </a>
    </td>
    <td width="33.3%" align="center" valign="top">
      <br>
      <a href="https://github.com/timoseyfarth/compose-shimmer-skeleton" target="_blank"><b>🩻 Compose Shimmer Skeleton</b></a>
      <p>Lightweight skeleton loader library for Jetpack Comose & KMP.</p>
      <a href="https://central.sonatype.com/artifact/dev.seyfarth/compose-shimmer-skeleton" target="_blank">
        <img src="https://img.shields.io/maven-central/v/dev.seyfarth/compose-shimmer-skeleton" alt="Compose Shimmer Skeleton Version">
      </a>
    </td>
    <td width="33.3%" align="center" valign="top">
      <br>
      <a href="https://github.com/timoseyfarth/smoothiepy" target="_blank"><b>🥤 Smoothiepy</b></a>
      <p>Smooth data streams like eye tracking or sensor input.</p>
      <a href="https://pypi.org/project/smoothiepy/" target="_blank">
        <img src="https://img.shields.io/pypi/v/smoothiepy" alt="PyPi Version">
      </a>
    </td>
  </tr>
  <tr>
    <td colspan="3"></td>
  </tr>
  <tr>
    <td colspan="3" align="center" bgcolor="#151515">
      <font size="5">🚀 <b>Featured Projects</b></font>
    </td>
  </tr>
  <tr>
    <td width="33.3%" align="center" valign="top">
      <br>
      <a href="https://spotify-code.seyfarth.dev" target="_blank"><b>🎵 Spotify Code Generator</b></a>
      <p>Turn any Spotify link into a scannable, 3D-printable tag.</p>
    </td>
    <td width="33.3%" align="center" valign="top">
      <br>
      <a href="https://github.com/timoseyfarth/wikipedia-race-ai" target="_blank"><b>🌐 Wikipedia Race AI</b></a>
      <p>AI-powered agent that plays the "Wikipedia Race" game.</p>
    </td>
    <td width="33.3%" align="center" valign="top">
      <br>
      <a href="https://github.com/fa25genai/orpheus" target="_blank"><b>🪉 Orpheus</b></a>
      <p>Transforms static slides into interactive lecture videos.</p>
    </td>
  </tr>
  <tr>
    <td colspan="3"></td>
  </tr>
  <tr>
    <td colspan="3" align="center" bgcolor="#151515">
      <font size="5">🔮 <b>In Progress</b></font>
    </td>
  </tr>
  <tr>
    <td width="33.3%" align="center" valign="top">
      <br>
      <p><b>📝 Markdown Form</b></p>
      <p>Use a custom dialect of the Markdown language to create online forms.</p>
    </td>
    <td width="33.3%" align="center" valign="top">
      <br>
      <p><b>🎶 Auralis</b></p>
      <p>AI-powered mobile music application. Cross-platform: Android & iOS.</p>
    </td>
    <td width="33.3%" align="center" valign="top">
      <br>
      <p><b>🖼️ SyncMoment</b></p>
      <p>Synced digital photo frame across households.</p>
    </td>
  </tr>
</table>

---

### 📕 Community Guestbook

This is a pixel grid guestbook for my GitHub profile. Every pixel represents a unique visitor who "signed" into my digital guestbook.
When you open an issue, a GitHub Action triggers a webhook to my server. The backend then downscales your profile picture to one pixel and injects it into the SVG image. After a few seconds it will appear here:

<div align="center">  
  </br>
  <a href="https://timo.seyfarth.dev/github/guestbook.svg" target="_blank">
    <img src="https://timo.seyfarth.dev/github/guestbook.svg" width="600" alt="Guestbook Grid">
  </a>

  
  <p align="center">
    <i>Click the grid to explore the interactive canvas in a new tab. Then <b>hover</b> a pixel to reveal the user's <b>quote</b> (if they entered one).</i>
  </p>
  </br>

  <a href="https://github.com/timoexample/repo/issues/new?template=guestbook.yml" target="_blank">
    <img src="https://img.shields.io/badge/Create%20issue%20to%20automatically%20add%20your%20pixel-7F52FF?style=for-the-badge&logo=accenture&logoColor=white" alt="Sign the Guestbook">
  </a>
</div>

---

### ✨ Development Philosophy

<table>
  <tr>
    <td width="50%">
      <p align="center"><b>UX (User Experience)</b></p>
      <p align="center">
        I believe that, these days, hardware resources are rarely the bottleneck. <b>Design and user experience are</b>. My goal is to create flawless, intuitive and playful user experiences.
      </p>
    </td>
    <td width="50%">
      <p align="center"><b>DX (Developer Experience)</b></p>
      <p align="center">
        I build systems that help me build systems. <b>Today's work solves tomorrow's problems</b>. I use structured, modular and reusable code wherever possible.
      </p>
    </td>
  </tr>
</table>

```kotlin
object Timo {
    fun codingPreferences(lang: Language): String = return when {
        lang == Language.KOTLIN -> {
            lang.syntacticSugar()
            "💖 Absolute favorite. DX peak."
        },
        lang == Language.JAVA -> {
            lang.histories().filter { it.is("Minecraft Plugins") }
            "☕ Where it all began. Respect roots."
        },
        lang == Language.PYTHON -> {
            lang.automateEverything()
            "🐍 Quick scripts & prototyping. Love the ease."
        },
        lang.isFrontend() -> {
            lang.applyCleanDesign()
            "🎨 UI / UX matters! Let's make it beautiful."
        },
        !lang.hasGarbageCollection() || lang == Language.C -> {
            lang.panicMode()
            "🌿 Pointers & MMM: Life is too short..."
        },
        else -> {
            "🛠️ Another tool in the belt."
        }
    }
}
```

---

<a name="tech-stack"></a>
### 🛠 Tech Stack

<div align="center">

  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=postgresql&logoColor=white" />

  <img src="https://img.shields.io/badge/Android-009639?style=for-the-badge&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />


  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />

  <img src="https://img.shields.io/badge/LaTeX-47A141?style=for-the-badge&logo=latex&logoColor=white" />
  <img src="https://img.shields.io/badge/3D_Modeling-FF9900?style=for-the-badge&logo=blender&logoColor=white" />
  <img src="https://img.shields.io/badge/3D_Printing-00A553?style=for-the-badge&logo=bambulab&logoColor=white" />
  <img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white" />
  <img src="https://img.shields.io/badge/and_much_more...-151515?style=for-the-badge&logo=more&logoColor=white" />

</div>
