<h1 align="center">Hi 👋, I'm Ahmet Cemil TOPRAK (hardhus)</h1>
<h3 align="center">Physics Undergraduate & Low-Level / Systems Software Developer from Türkiye</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=hardhus&label=Profile%20views&color=0e75b6&style=flat-square" alt="hardhus" />
  <img src="https://img.shields.io/github/followers/hardhus?label=Followers&style=flat-square&color=211F1F" alt="followers" />
</p>

---

### 💫 About Me
Yıldız Teknik Üniversitesi Fizik bölümü öğrencisiyim. Bilgisayar donanımına yakın, yüksek performans ve optimizasyon gerektiren alt seviye (low-level) sistem yazılımlarına, FPGA tabanlı sayısal tasarımlara ve modern asenkron ağ mimarilerine derin bir tutku duyuyorum. 

Teorik altyapıyı, ultra düşük gecikmeli sistemlerden donanımsal USB emülatörlerine kadar uzanan pratik ve karmaşık projelerle birleştirmeyi seviyorum.

* 🎓 **Education:** Physics, Yıldız Technical University (2019 - 2026)
* 📍 **Location:** İstanbul, Türkiye
* ✉️ **Contact:** ahmetcemiltoprakk@gmail.com
* 🛠️ **Focus:** Low-Level Systems, High-Frequency Trading (HFT) Infrastructure, FPGA/Digital Design, Async Networking.

---

### 🛠️ Languages & Technologies

<table align="center">
  <tr>
    <td align="center" width="120">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="40" height="40" alt="C++" /><br /><b>C++ (C++20)</b>
    </td>
    <td align="center" width="120">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-original.svg" width="40" height="40" alt="Rust" /><br /><b>Rust (Async/TUI)</b>
    </td>
    <td align="center" width="120">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" height="40" alt="TypeScript" /><br /><b>TypeScript</b>
    </td>
    <td align="center" width="120">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" height="40" alt="Python" /><br /><b>Python</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="120">
      <img src="https://raw.githubusercontent.com/file-icons/icons/master/svg/SystemVerilog.svg" width="40" height="40" alt="SystemVerilog" /><br /><b>SystemVerilog / VHDL</b>
    </td>
    <td align="center" width="120">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="40" height="40" alt="Node.js" /><br /><b>Node.js / Bun</b>
    </td>
    <td align="center" width="120">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="40" height="40" alt="PostgreSQL" /><br /><b>PostgreSQL / Sled</b>
    </td>
    <td align="center" width="120">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="40" height="40" alt="React" /><br /><b>React / Next.js</b>
    </td>
  </tr>
</table>

---

### 📂 Highlighted Projects

#### ⚡ Low-Level, HFT & Systems Programming
* **[NanoMatch](https://github.com/hardhus/NanoMatch):** High-Frequency Trading (HFT) için geliştirilmiş; donanımsal bit tarama intrinsics (`TZCNT`/`BSR`), sıfır-allokasyon nesne havuzları (`ObjectPool`) ve intrusive çift yönlü listeler kullanan deterministik $O(1)$ çalışma zamanlı, ultra düşük gecikmeli eşleştirme motoru. *(C++20, STL)*
* **[Pico-Ducky-v2](https://github.com/hardhus/pico_ducky):** Raspberry Pi Pico tabanlı, yerleşik 1.5 MB flash disk barındıran ve TR-Q klavye düzenine destek veren donanımsal bir Rubber Ducky (BadUSB) betik yürütücü aracı. *(C++, Pico SDK, TinyUSB)*
* **[Nodexel](https://github.com/hardhus/nodexel):** C++17 ve OpenGL3 mimarisi üzerine kurulu, retro piksel sanatı, palet eşleme ve gölgeleme efektleri üreten düğüm tabanlı (Node-based) asenkron grafik motoru. Ağır görüntü işleme algoritmalarını `std::thread` ve thread-safe çiftleme tamponları (`std::mutex`) kullanarak arayüz iş parçacığından (UI thread) tamamen soyutlar ve kesintisiz 60+ FPS donanım hızlandırmalı bir akış sağlar. *(C++, OpenGL3, ImGui, ImNodes)*
* **[Quake](https://github.com/hardhus/quake):** Chumsky kütüphanesi kullanılarak geliştirilmiş lexer, parser ve Rust köprülü (Native stdlib) bir soyut sözdizimi ağacına (AST) sahip, özel yapım programlama dili yorumlayıcısı. *(Rust, Chumsky)*
* **[Crusty-Audio-Engine](https://github.com/hardhus/crusty-audio-engine) & [Lang](https://github.com/hardhus/crusty-audio-lang):** ADSR, filtreler ve sequencer barındıran modüler, thread-safe bir dijital ses sentezleme motoru (DSP) ve bu motoru hedef alan özel ses betik dili derleyicisi. *(Rust, CPAL)*

#### 📡 Hardware & Digital Design (FPGA)
* **[FPGA-Digital-Design-Labs](https://github.com/hardhus/fpga-handbook):** Basit kapılardan başlayıp FSM hesap makineleri, PDM/PWM ses işlemcileri ve AXI tabanlı Kripto/Yapay Zeka yüzen nokta (Floating-Point) DSP birimlerine uzanan dual-HDL sayısal tasarım deposu. *(SystemVerilog, VHDL, Vivado/XSIM)*
* **[HFT-FeedHandler-OrderEvaluator](https://github.com/hardhus/HFT-FeedHandler-OrderEvaluator):** HFT işlemleri için donanım tabanlı UDP paket çözücü (Parser) ve emir değerlendirici projesi *(Geliştirme Aşamasında)*. *(SystemVerilog, C++, Vivado)*

#### 🦀 Modern Full-Stack & Ecosystem Tools
* **[Moku](https://github.com/hardhus/moku):** Argon2 ve AES-GCM kriptografik güvenli kasaya sahip; Bookmark, Todo, Sistem İzleme ve Gemini API destekli AI Commit mesajı üretici barındıran modüler TUI verimlilik platformu. *(Rust, Ratatui, Sled DB, Tokio)*
* **[Crusty Audio Live Studio](https://github.com/hardhus/crusty_audio):** Rust ile yazılmış lock-free modüler ses sentezleyici motoru ile anlık derleme yapabilen özel DSL (Domain-Specific Language) derleyicisini WebAssembly (WASM) köprüsüyle tarayıcıya taşıyan canlı müzik kodlama ve DSP stüdyosu. *(Rust, WebAssembly, React 19, TypeScript, Tailwind v4)*
* **[Rust-Hexagonal-Architecture](https://github.com/hardhus/rust_backend_template):** Domain-Driven Design (DDD) prensiplerine uygun; derleme zamanı doğrulamalı değer nesneleri barındıran Axum ve SQLx tabanlı Hexagonal mimari şablonu. *(Rust, Axum, SQLx, Tokio)*
* **[TaskHub](https://github.com/hardhus/taskhub):** Sürükle-bırak özellikli, gelişmiş ve gerçek zamanlı bir Kanban/Görev yönetim uygulaması. *(TypeScript, Bun, Express, React, PostgreSQL)*

---

### 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hardhus&show_icons=true&locale=en&theme=dracula&hide_border=true" alt="hardhus GitHub Stats" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=hardhus&show_icons=true&locale=en&layout=compact&theme=dracula&hide_border=true&langs_count=6" alt="hardhus Top Languages" height="150" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=hardhus&theme=dracula&hide_border=true" alt="hardhus Streak" />
</p>

---

### 🤝 Connect with me
* **Email:** ahmetcemiltoprakk@gmail.com
