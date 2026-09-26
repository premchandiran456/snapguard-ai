# snapguard-ai

All inference runs **locally** — optimized to leverage the **Snapdragon NPU** for fast, power-efficient, real-time processing on Snapdragon-powered HP PCs.

## ✨ Key Features

| Feature | Description |
|---|---|
| 🔍 **Smart PII Detection** | Auto-identifies Aadhaar numbers, phone numbers, emails |
| 🎭 **Face & Signature Redaction** | YOLOv5-based detection with auto-blur |
| ⚡ **On-Device Inference** | Zero cloud dependency, NPU-accelerated |
| 📄 **Multi-Format Support** | Works on scanned docs, photos, screenshots |
| 🔒 **Privacy by Design** | Nothing ever leaves your device |

## 🛠️ Tech Stack

- **Computer Vision:** YOLOv5 (face/signature detection)
- **OCR:** EasyOCR / Tesseract (text & PII extraction)
- **Backend:** Python, Flask
- **Target Hardware:** Snapdragon-powered HP PCs (NPU-accelerated)
- **Planned Optimization:** Qualcomm AI Hub model conversion for on-device NPU inference

## 🎯 Real-World Impact

- **Students & Job Seekers** — safely share ID proofs without exposing personal data
- **Digital KYC Platforms** — pre-process documents before storage/transmission
- **Enterprises** — internal document handling with built-in compliance-friendly redaction
- **Everyday Users** — protect screenshots before posting or forwarding

## 🚀 Why Snapdragon?

SnapGuard AI's entire value proposition — **privacy through on-device processing** — depends on fast, efficient local inference. Snapdragon's dedicated **NPU (Neural Processing Unit)** makes this possible without draining battery or requiring powerful discrete GPUs, making privacy protection accessible on everyday Snapdragon-powered HP PCs.

## 🗺️ Roadmap

- [ ] Convert YOLOv5 + OCR pipeline to Qualcomm AI Hub-optimized models
- [ ] Benchmark NPU vs CPU inference speed on Snapdragon HP PCs
- [ ] Build desktop UI for drag-and-drop document redaction
- [ ] Add support for more ID types (PAN, Voter ID, Passport)

## 👤 Developer

**Premchandiran**
B.Tech Computer Science and Engineering 
Manakula Vinayagar Institute of Technology (MVIT), Puducherry

## 📌 Status

🚧 **In active development** — submitted for Snapdragon® AI Lab Build & Present Challenge (Solution Submission Round)





