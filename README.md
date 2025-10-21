<div align="center">

<!-- Animated Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=ENFUIR&fontSize=80&fontAlignY=35&animation=twinkling&fontColor=fff" width="100%"/>

<img src="mario-hacker.png" width="200" style="border-radius: 50%; border: 3px solid #58A6FF; box-shadow: 0 0 20px #58A6FF;">

# 👾 Hi, I'm Enfuir

### 🔥 Low-Level Systems Researcher | IOMMU Bypass Specialist | Hypervisor Developer

<img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="600">

<!-- Animated Typing Effect -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=900&lines=AMD+SVM+%26+Intel+VMX+Hypervisor+Development+%F0%9F%9A%80;IOMMU+%2F+VT-d+Bypass+Techniques+%F0%9F%94%93;Windows+Kernel+Driver+Development+%F0%9F%92%BB;UEFI+%2F+BIOS-Level+Programming+%E2%9A%A1;Anti-Cheat+Evasion+Research+%F0%9F%9B%A1%EF%B8%8F;DMA+Attack+Development+%F0%9F%8E%AF;Ring+-1+to+Ring+0+Exploitation+%F0%9F%94%A5)](https://git.io/typing-svg)

<!-- Badges with Glow Effect -->
<p align="center">
  <img src="https://img.shields.io/badge/Ring--1-Hypervisor-ff0000?style=for-the-badge&logo=amd&logoColor=white" />
  <img src="https://img.shields.io/badge/Ring_0-Kernel-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/UEFI-Firmware-00ADD8?style=for-the-badge&logo=uefi&logoColor=white" />
  <img src="https://img.shields.io/badge/DMA-Hardware-FF6B6B?style=for-the-badge&logo=raspberrypi&logoColor=white" />
  <img src="https://img.shields.io/badge/IOMMU-Bypass-9B59B6?style=for-the-badge&logo=intel&logoColor=white" />
</p>

<!-- Profile Views Counter -->
<img src="https://komarev.com/ghpvc/?username=Enfuir&color=blueviolet&style=for-the-badge&label=👁️+PROFILE+VIEWS" alt="Profile Views" />

</div>

---

<div align="center">

## 🛠️ Technology Arsenal

### Languages & Low-Level Tools

<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Assembly-654FF0?style=for-the-badge&logo=assemblyscript&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
</p>

### Kernel & System Development

<p align="center">
  <img src="https://img.shields.io/badge/Windows_Kernel-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux_Kernel-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/UEFI-0E76A8?style=for-the-badge&logo=uefi&logoColor=white" />
  <img src="https://img.shields.io/badge/AMD_SVM-ED1C24?style=for-the-badge&logo=amd&logoColor=white" />
  <img src="https://img.shields.io/badge/Intel_VMX-0071C5?style=for-the-badge&logo=intel&logoColor=white" />
</p>

### Reverse Engineering & Debugging

<p align="center">
  <img src="https://img.shields.io/badge/WinDbg-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/IDA_Pro-000000?style=for-the-badge&logo=ida&logoColor=white" />
  <img src="https://img.shields.io/badge/Ghidra-EF3B2D?style=for-the-badge&logo=ghidra&logoColor=white" />
  <img src="https://img.shields.io/badge/x64dbg-1E88E5?style=for-the-badge&logo=x64dbg&logoColor=white" />
  <img src="https://img.shields.io/badge/Cheat_Engine-FF6B6B?style=for-the-badge&logo=cheatengine&logoColor=white" />
</p>

</div>

---

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">

## 🎯 Research Focus Areas

<table>
<tr>
<td width="50%">

### 🔓 Virtualization & Hypervisors
```assembly
; AMD SVM Hypervisor
mov eax, 0x8000000A
cpuid
test ecx, 1 << 2  ; SVME support
jz no_svm
vmrun                ; Enter guest mode
```

**Focus:**
- Custom Type-1 Hypervisors
- EPT/NPT Manipulation
- VMCS/VMCB Hooking
- VM Exit Handling

</td>
<td width="50%">

### ⚡ IOMMU/VT-d Bypass
```c
// IOMMU Bypass Technique
PHYSICAL_ADDRESS pa;
pa = MmGetPhysicalAddress(va);
// Direct DMA access
DMA_Write(pa, buffer, size);
```

**Focus:**
- PCIe DMA Attacks
- IOMMU Remapping Bypass
- Scatter-Gather I/O
- TLP Injection

</td>
</tr>
<tr>
<td width="50%">

### 🛡️ Anti-Cheat Evasion
```cpp
// Kernel-Mode Driver
NTSTATUS DriverEntry() {
    // Hide from PatchGuard
    DisablePatchGuard();
    // Hook SSDT
    HookSystemService();
    return STATUS_SUCCESS;
}
```

**Focus:**
- Kernel Driver Development
- SSDT/Shadow SSDT Hooks
- PatchGuard Bypass
- Hypervisor-Based Cheats

</td>
<td width="50%">

### 🌌 UEFI/BIOS Programming
```c
// UEFI Runtime Services
EFI_STATUS SetVariable(
    CHAR16 *VariableName,
    EFI_GUID *VendorGuid,
    UINT32 Attributes,
    UINTN DataSize,
    VOID *Data
);
```

**Focus:**
- UEFI Bootkit Development
- SMM Mode Exploitation
- Secure Boot Bypass
- Firmware Rootkits

</td>
</tr>
</table>

</div>

---

<div align="center">

## 📊 GitHub Statistics

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Enfuir&show_icons=true&theme=radical&hide_border=true&count_private=true&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&text_color=C9D1D9&include_all_commits=true&custom_title=Enfuir's+GitHub+Stats" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=Enfuir&theme=radical&hide_border=true&background=0D1117&stroke=58A6FF&ring=58A6FF&fire=FF6B6B&currStreakLabel=58A6FF&sideLabels=C9D1D9" />

<img width="60%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Enfuir&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&hide=html,css,javascript&langs_count=8&custom_title=Most+Used+Languages" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Enfuir&theme=react-dark&hide_border=true&area=true&bg_color=0D1117&color=58A6FF&line=58A6FF&point=FF6B6B&custom_title=Contribution+Graph" width="98%" />

</div>

---

<div align="center">

## 🏆 GitHub Trophies

<img src="https://github-profile-trophy.vercel.app/?username=Enfuir&theme=radical&no-frame=true&no-bg=true&column=7&margin-w=15&margin-h=15" width="100%" />

</div>

---

<div align="center">

## 🔥 Current Projects

<table>
<tr>
<td width="33%" align="center">
<img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="100">
<h3>Hypervisor Development</h3>
<p>Custom AMD SVM & Intel VMX hypervisors for stealth and security research</p>
</td>
<td width="33%" align="center">
<img src="https://user-images.githubusercontent.com/74038190/212257468-1e9a91f1-b626-4baa-b15d-5c385dfa7ed2.gif" width="100">
<h3>DMA Cheats</h3>
<p>Hardware-based game manipulation using PCIe DMA cards</p>
</td>
<td width="33%" align="center">
<img src="https://user-images.githubusercontent.com/74038190/212257465-7ce8d493-cac5-494e-982a-5a9deb852c4b.gif" width="100">
<h3>Kernel Drivers</h3>
<p>Windows kernel-mode drivers for system-level access</p>
</td>
</tr>
</table>

</div>

---

<div align="center">

## 🎮 Featured Repositories

<a href="https://github.com/Enfuir/BF6-DMA-Cheat">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Enfuir&repo=BF6-DMA-Cheat&theme=radical&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&text_color=C9D1D9" />
</a>

</div>

---

<div align="center">

## 💬 Connect With Me

<p align="center">
  <a href="https://discord.gg/your-discord"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>
  <a href="https://twitter.com/your-twitter"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" /></a>
  <a href="mailto:your-email@example.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

</div>

---

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## ⚠️ Legal Disclaimer

**All projects and research are strictly for educational and security research purposes only.**

This profile showcases technical research in low-level systems programming, virtualization, and hardware security. All code and techniques are intended to advance knowledge in cybersecurity and should only be used in authorized testing environments.

**Use responsibly. Respect all applicable laws and regulations.**

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>

