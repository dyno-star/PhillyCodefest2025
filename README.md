♻️ B.A.G.S. - The Future of Smarter Recycling 🚀

We all know recycling isn’t perfect, but trying to do the right thing shouldn’t make you feel like a waste of space! 🗑️ That’s where B.A.G.S. (Basic Artificial Garbage Sorter) 🛍️🤖 comes in.

Plastic bags are one of the biggest culprits in contaminating recycling bins, making entire loads of recyclable materials unusable. ❌ B.A.G.S. uses cutting-edge AI to detect plastic bags before they end up where they don’t belong. ✅

🛠️ How It Works

Our system is powered by OpenCV 📷 for image processing and YOLO (You Only Look Once) 🦾 for object detection. The backend is built in Python 🐍, and we’ve custom-trained a model to recognize different types of plastic bags with an impressive 70-90% confidence rate! 🎯

With more time and refinement, we can improve accuracy and expand detection capabilities to other non-recyclables like bubble wrap 🫧, plastic straws 🥤, and more.

🌐 Building the Website

Want to get B.A.G.S. up and running? Here’s how to do it:

🔧 Command Options

Run the following command with the necessary parameters:

python app.py --ip 0.0.0.0 --port 8000 -m paty_kerry.pt


🛠️ Available Flags:

📌 -i or –ip → IP address of the device (Required)
📌 -o or –port → Port number for the server (Required)
📌 -f or –frame_count → Number of frames used to construct the background model (Default: 32)
📌 -m or –model → AI Model to use (Options: katy_perry.pt 🎤, paty_kerry.pt 🎶, Default: katy_perry.pt)
📌 -b or –backend → Backend to use (Options: cuda ⚡, cpu 🖥️, Default: cuda if available, otherwise cpu)

🙏 Acknowledgments

This project wouldn’t be possible without these amazing tools:

🔹 OpenCV 📸 - © 2000-2025 OpenCV.org (Licensed under Apache-v2.0)
🔹 Ultralytics 🧠 - © 2023-2025 Ultralytics (Licensed under AGPL-v3.0)

🌍 Together, we can make recycling smarter! ♻️ 🚀
