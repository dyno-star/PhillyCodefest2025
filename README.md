
♻️ **B.A.G.S. - The Future of Smarter Recycling** 🚀  

Recycling is broken, but fixing it shouldn’t feel like rocket science! 🛸 Enter **B.A.G.S.** (**Basic Artificial Garbage Sorter**) 🛍️🤖, an AI-powered solution designed to tackle one of recycling’s biggest headaches: **plastic bag contamination**.  

Plastic bags are notorious for ruining entire batches of recyclables, sending them straight to landfills. ❌ B.A.G.S. uses cutting-edge AI to detect and prevent plastic bags from contaminating recycling bins, ensuring cleaner, more efficient recycling. ✅  

---

🛠️ **How It Works**  

B.A.G.S. combines **OpenCV** 📷 for image processing and **YOLO (You Only Look Once)** 🦾 for real-time object detection. Built in Python 🐍, our custom-trained model identifies plastic bags with **70-90% accuracy** 🎯—and we’re just getting started!  

With further refinement, B.A.G.S. can expand to detect other non-recyclables like **bubble wrap** 🫧, **plastic straws** 🥤, and more.  

---

🌐 **Getting Started**  

Ready to deploy B.A.G.S.? Here’s how:  

🔧 **Command Options**  
Run the following command with the necessary parameters:  

```bash
python app.py --ip 0.0.0.0 --port 8000 -m paty_kerry.pt
```

🛠️ **Available Flags**  
- **-i / --ip**: IP address of the device (Required)  
- **-o / --port**: Port number for the server (Required)  
- **-f / --frame_count**: Number of frames for background model (Default: 32)  
- **-m / --model**: AI model to use (Options: `katy_perry.pt` 🎤, `paty_kerry.pt` 🎶, Default: `katy_perry.pt`)  
- **-b / --backend**: Backend to use (Options: `cuda` ⚡, `cpu` 🖥️, Default: `cuda` if available, otherwise `cpu`)  

---

🙏 **Acknowledgments**  

B.A.G.S. wouldn’t exist without these incredible tools:  
- **OpenCV** 📸 - © 2000-2025 OpenCV.org (Licensed under Apache-v2.0)  
- **Ultralytics** 🧠 - © 2023-2025 Ultralytics (Licensed under AGPL-v3.0)  

---

🌍 **Together, Let’s Make Recycling Smarter!** ♻️ 🚀  

---

