<h1 style="text-align:center;"><b>INSTRUCTION_N_RULES</b></h1>

Virose organization work instruction and rules

<h3 style="text-align:center; margin: 5px 0;
"> Content: </h3>
<ul style="display: flex; padding: 0; gap: 10px; justify-content: center; 
list-style-type: none;">
  <li >
    •<a href="#rules-section">Rules</a>
  </li>
  <li>
    •<a href="#github-section">Github</a>
  </li>
  <li>
    •<a href="#instruction-section">Instruction</a>
  </li>
</ul>

---

<!-- RULES -->

<h1 style="text-align:center;" id="rules-section">
    <b>RULES</b>
</h1>

<details open>
<Summary style="font-weight:bold; " > GENERAL</Summary>
<b>Struktur penamaan repository:</b><br>
<code>
[DIVISI]_[TAG DIVISI]_[NAMA]_[KETERANGAN(optional)]
</code>

<p>
<br><b>Aturan penamaan repository:</b><br>
1. Gunakan nama yang deskriptif dan singkat.<br>
2. TAG DIVISI disesuaikan dengan divisi masing-masing.<br>
3. Gunakan underscore (_) untuk memisahkan kata.<br>

Contoh:<br>
PRG_ROBOT_SUB_PROGRAM<br>

DIVISI<br>
PRG: Programming<br>
MCH: Mechanic<br>
ELC: Electrical<br>

</p>

<p>
<b>Aturan Commit</b>:<br>
[ACTION]_[KETERANGAN]<br>   
1. Gunakan bahasa Inggris atau Indonesia yang jelas dan singkat.<br>

Action:<br>

- ADD: untuk penambahan fitur atau file baru<br>
- FIX: untuk perbaikan bug atau kesalahan<br>
- CHORE: Minor addition
- REMOVE: untuk penghapusan fitur atau file<br>
- REFACTOR: untuk perubahan struktur kode tanpa mengubah fungsionalitas<br>
- DOC: untuk perubahan pada dokumentasi<br>

</p>
</details>

<br>

<details open>
<Summary style="font-weight:bold; " > PROGRAMMING</Summary>
<p>
<b>TAG DIVISI:</b>
<ul>
<li>ROBOT: untuk program robot utama </li>
<li>SUB: untuk program pendukung robot</li>
<li>TOOLS: untuk program alat bantu</li>
<li>WEB: untuk program website</li>
<li>INTERFACE: untuk program interface robot</li>
<li>ESP32/ARDUINO: untuk program microcontroller ESP32/Arduino</li>
<li>TEST: untuk repo testing</li>
</ul>
</p>
<p>
<b>ATURAN:</b>
</p>
<ul>
<li>Penugasan akan ditaruh notion</li>
<li>Buat branch baru buat setiap penugasan yang bersifat adding</li>
<li>Integrasi harus lewat PULL REQUEST dan menunggu code review</li>
</ul>

</details>

<br>

<details open>
<Summary style="font-weight:bold; " > MECHANIC</Summary>
<p>
<b>TAG DIVISI:</b>
<ul>
<li>None </li>

</ul>
</p>
<p>
<b>ATURAN:</b>
</p>
<ul>
<li>None</li>
</ul>
</details>

<br>

<details open>
<Summary style="font-weight:bold; " > ELECTRICAL</Summary>
<b>TAG DIVISI:</b>
<ul>
<li>None </li>

</ul>
</p>
<p>
<b>ATURAN:</b>
</p>
<ul>
<li>None</li>
</ul>
</details>

---

<!-- GITHUB -->
<h1 style="text-align:center;" id="github-section">
    <b>GITHUB</b>
</h1>

<details open>
<Summary style="font-weight:bold; " > BRANCH</Summary>

branching gae feature

</details>

<details open>
<Summary style="font-weight:bold; " > RELEASE</Summary>

Rilis fungsional

</details>

---

<!-- INSTRUCTION -->

<h1 style="text-align:center;" id="instruction-section">
    <b>INSTRUCTION</b>
</h1>

<details open>
<Summary style="font-weight:bold; " > PREQUISITES</Summary>
<ol>
<li>Buat akun <a href="https://github.com/signup">Github</a></li>
<li>Install <a href="https://git-scm.com/downloads">Git</a></li>
<li>Install <a href="https://code.visualstudio.com/">Vscode</a> (optional tapi disarankan)</li>
</ol>

</details>

<details open>
<Summary style="font-weight:bold; " > SETUP</Summary>

<h4><b>GIT</b></h4>
1. Buka terminal / command prompt<br>
2. Set username sama email git lewat terminal<br>
<code>
git config --global user.name "username" <br>
git config --global user.email "email@example.com"
</code>

<h4><b>VSCODE</b></h4>
1. Login github di Vscode<br>
<img src="./assets/git_vscode.png">

<h4><b>SSH</b></h4>

</details>

<details open>
<Summary style="font-weight:bold; " > CONTRIBUTE</Summary>

Buat Repo

Clone Repo

Commit

Push

</details>
