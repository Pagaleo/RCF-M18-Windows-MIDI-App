# 🎛️ RCF M18 Windows MIDI App

A standalone Windows application to remotely control select functions of the **RCF M18 Digital Mixer** via MIDI – no tablet, no Wi-Fi, just standard MIDI.

---

## 🎯 Features

- Control main volume faders:
  - ✅ Main Out
  - ✅ Phones
  - ✅ AUX1–AUX6
- Store and recall **Snapshots**
- Trigger snapshots via MIDI Program Change
- Simple MIDI **Player controls** (Play / Stop / Prev / Next)
- MFX Patch switching (Previous / Next per slot)
- Fully offline use – requires only a basic USB-MIDI interface

---

## 💡 Use Cases

- 🎚 FOH AUX Level Control via MIDI
- 🎧 Adjust In-Ear Monitor levels easily
- 🏠 Zone volume control in multi-room setups
- 🎤 Fast switching between show configurations
- 🔁 Load mixer scenes with a single click

> Especially helpful in live, rehearsal or venue environments  
> where a fast and Wi-Fi-free solution is needed.

---

## 🚫 Limitations (due to RCF’s limited MIDI spec)

- ❌ No individual channel controls (volume, EQ, pan etc.)
- ❌ No feedback from the M18 (no patch names, no status sync)
- ❌ No real-time parameter reads

---

## 🔧 Requirements

- Windows PC (tested on Windows 10 and 11)
- RCF M18 Mixer
- Standard USB-to-MIDI interface (e.g., Roland UM-One, Miditech, etc.)
- Python not required – this is a compiled `.exe`

---

## 🧭 How to Use

1. Connect your MIDI interface to the M18 (MIDI OUT → IN)
2. Launch `rcf_m18_midi.exe`
3. Select the correct MIDI output port
4. Start controlling levels and snapshots
5. Save and load configurations as needed

---

## 📦 What’s Included

- ✅ `rcf_m18_midi.exe` (the application)
- ✅ Snapshot folder with examples
- ✅ `snapshot_labels.json` (naming presets)
- ✅ User Manuals (EN / DE / IT)
- ✅ GUI Screenshot

---

## 📈 Roadmap / Vision

- Explore possible feedback support if RCF expands MIDI spec
- Add customizable snapshot slots
- Potential macOS version via Python cross-compilation

---

## 🧑‍💻 Developer

Made with ❤️ by **Uwe Müller**  
If you're looking for a remote / freelance developer with real-world MIDI + UI skills – get in touch!

---

## 📄 License

MIT License – use it, modify it, share it. Just don’t remove credit.

---


