# Size It Up & Weigh It Up

Two real-world scale guessing games. Play solo or in multiplayer rooms.

- **Size It Up:** resize the red silhouette to its real size next to a known object. 162 objects.
- **Weigh It Up:** a balance scale holds one object. Guess how many of the red object it takes to balance it. 101 objects with typical weights.

## Host on GitHub Pages
1. Upload `index.html` and `assets.js` to the same folder of your repo.
2. Go to Settings → Pages, choose your branch, and save. Open your Pages link.

## Play with friends
1. Pick a game, type your name, and click **Create room**.
2. Click **Copy**, **Send on WhatsApp** or **Share…** (on phones) to send the invite link.
3. Set **Players needed to start**. **Start game** unlocks once enough people have joined.
4. The host can switch between the two games in the lobby. **⌂ Home** leaves the room at any time.

The host's page must stay open, because the host is the room. Rooms connect through the free PeerJS service. If someone on mobile data can't join, switching to Wi-Fi usually helps.
To test on one computer: open `index.html?net=local`, create a room, then open the invite link in another tab.

## Controls
- **Size It Up:** pinch with two fingers, drag the ⤢ handle, or use the slider to resize. Drag the shape to move it. **+ / −** zoom only the view.
- **Weigh It Up:** type a number, or use **÷2 − + ×2** or the slider. The scale stays pinned until you lock in, so it can't give the answer away.
- **Keyboard:** arrow keys adjust your answer. Enter locks in, then goes to the next round.
