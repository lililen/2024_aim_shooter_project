# Python Mini Projects — Aim Trainer & Phubbing Tracker

My first Python projects (2024), built to practice game development and computer vision.

---

## P1 — Aim Trainer Game

A fast-paced aim trainer built with **Pygame**, inspired by rhythm games.

**How to play:**
- Click targets as close to the center as possible within 30 seconds
- Targets respawn at a random position after each click

**Scoring:**
| Zone | Points |
|------|--------|
| Center (red) | 5 pts |
| Middle (orange) | 3 pts |
| Outer (yellow) | 1 pt |
| Miss | 0 pts |

Final screen shows your **score** and **accuracy %**.

**Run:**
```bash
pip install pygame
python P1_aim_trainer.py
```

---

## P2 — Phubbing Tracker

A webcam-based focus tracker built with **OpenCV**, **Tkinter**, and **Pillow**, inspired by psychology research on phubbing (phone snubbing).

Uses face detection to determine whether you're looking at your screen or at your phone. Tracks cumulative phubbing time vs focus time in real time.

**Features:**
- Live webcam feed in a Tkinter GUI
- Face detected → "Phubbing" status + timer
- No face → "Focused" status + timer
- Reset button to clear session stats

**Run:**
```bash
pip install opencv-python pillow
python P2_phubbing.py
```

> Requires a webcam. Uses OpenCV's built-in Haar cascade for face detection.

---

## Stack

- Python 3
- Pygame
- OpenCV (cv2)
- Tkinter
- Pillow
