# ⚡ WinperPacker for macOS (Apple Silicon M1 / M2 / M3 / M4)

**Wrap any Windows `.exe` — work utilities, legacy software, or DirectX/Steam games — into a standalone native macOS `.app` in seconds.**

🌐 **Official Website & Download (First `.app` Build Free):** [https://winperpacker.vercel.app](https://winperpacker.vercel.app)

---

### ✨ Key Features
* **No Heavy VMs:** Skip 40 GB virtual machines and \$100/year subscriptions just to run Windows `.exe` programs on your MacBook.
* **Classic Mode (`32bit = 64bit`):** Isolated 32-bit compatibility wrapper powered by DXVK + MoltenVK for Windows utilities, installers, and classic DirectX 9 apps — with automatic `.exe` icon extraction.
* **DX12 Metal Mode (`DX12 = Metal`):** Hardware-accelerated Apple D3DMetal + MetalFX + MSync engine for graphics-heavy 64-bit apps and modern DirectX 11/12 games.
* **Steam Online:** One-click setup and launch of a pre-configured `Steam Winper.app` with an instant Close Steam toggle.
* **Your `.app` Files Work Forever:** Even after your free build or `5-Pack Pass ($2)` runs out, every `.app` you already created keeps launching forever — you only pay if you want to pack new ones.

### 🚀 Quick Start
1. Download `WinperPacker-1.0-macOS.zip` from **[winperpacker.vercel.app](https://vercel.app)** or the **Releases** tab.
2. Move `WinperPacker.app` to **Applications**.
3. On first launch, run in Terminal if macOS Gatekeeper prompts:
   ```bash
   xattr -cr /Applications/WinperPacker.app
   ```
4. Drop any Windows `.exe`, pick **Classic** or **DX12 Metal**, and click **Pack `.exe` = `.app`**.
