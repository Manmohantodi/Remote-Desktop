# Remote Desktop Sharing System

## Overview
This project implements a Remote Desktop Sharing System using Python. The server captures the screen and sends it to the client, while the client can view the screen and control mouse movements remotely.

## Features
- Real-Time Screen Sharing
- Mouse Control Support (Move, Left Click, Right Click)
- Multi-Threaded Server for handling multiple clients
- Graphical Client Interface (Tkinter)

## Technologies Used
- Python (sockets, threading, PIL, pyautogui)
- GUI Development (Tkinter)
- Image Processing (Pillow)
- Networking (TCP Sockets)

## Project Structure
```
/Remote-Desktop
│── RemoteDeskServer.py    # Server-side script
│── RemoteDeskClient.py    # Client-side script
│── README.md              # Project documentation
│── requirements.txt       # Dependencies
│── .gitignore             # Ignore unnecessary files
│── LICENSE                # License information (optional)
```

## Installation & Usage
1. Clone the repository
```bash
git clone https://github.com/Manmohantodi/Remote-Desktop.git
cd Remote-Desktop
```

2. Install Dependencies
```bash
pip install -r requirements.txt
```

3. Start the Server
```bash
python RemoteDeskServer.py
```

4. Start the Client
```bash
python RemoteDeskClient.py
```

## Future Enhancements
- Implement keyboard control support
- Add multi-client support
- Improve image compression for efficiency

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
If you find this project useful, give it a star!

