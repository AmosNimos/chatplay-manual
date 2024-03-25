# chatplay-manual
Manual for the control chat command for my livestream

---

## YouTube Chat Control Script Manual

This script allows you to control your computer's keyboard and mouse actions based on keywords detected in the YouTube chat popup window.

### Keywords and Actions

- `kup`: Simulates pressing and holding the 'W' key.
- `kdown`: Simulates pressing and holding the 'S' key.
- `kleft`: Simulates pressing and holding the 'A' key.
- `kright`: Simulates pressing and holding the 'D' key.
- `kspace`: Simulates pressing and holding the 'Space' key.
- `kclick`: Simulates a mouse click.
- `kctrl`: Simulates pressing and holding the 'Ctrl' key.
- `mup`: Moves the mouse cursor up by a specified number of pixels.
- `mdown`: Moves the mouse cursor down by a specified number of pixels.
- `mleft`: Moves the mouse cursor left by a specified number of pixels.
- `mright`: Moves the mouse cursor right by a specified number of pixels.
- `rel`: Releases a specific key.
- `key`: Simulates pressing and holding a specified key. Use `-` followed by the key name (e.g., `key-a`).
- `mrel`: Releases the mouse button (left by default, or specify 'right' with `-right`).
- `​​rspace`: Releases the 'Space' key.
- `​​rup`: Releases the 'Up' arrow key.
- `​​rdown`: Releases the 'Down' arrow key.
- `​​rleft`: Releases the 'Left' arrow key.
- `​​rright`: Releases the 'Right' arrow key.

### How to Use

1. Send messages in the chat with the specified keywords to trigger actions.
2. Use the keywords to control keyboard and mouse actions on the computer.

### Example

- To move the mouse cursor up by 50 pixels, send the message `mup-50`.
- To simulate pressing and holding the 'W' key, send the message `key-w`.
- To simulate a mouse click, send the message `kclick`.

---


- `cleft hold`: Holds the left mouse button.
- `cleft`: Performs a single click with the left mouse button.
- `cright hold`: Holds the right mouse button.
- `cright`: Performs a single click with the right mouse button.
- `kup`: Simulates pressing and holding the 'W' key.
- `kdown`: Simulates pressing and holding the 'S' key.
- `kleft`: Simulates pressing and holding the 'A' key.
- `kright`: Simulates pressing and holding the 'D' key.
- `kspace`: Simulates pressing and holding the 'Space' key.
- `kclick`: Simulates a mouse click.
- `kctrl`: Simulates pressing and holding the 'Ctrl' key.
- `mup-50`: Moves the mouse cursor up by 50 pixels.
- `mdown-50`: Moves the mouse cursor down by 50 pixels.
- `mleft-50`: Moves the mouse cursor left by 50 pixels.
- `mright-50`: Moves the mouse cursor right by 50 pixels.
- `rel-w`: Releases the 'W' key.
- `rel-s`: Releases the 'S' key.
- `rel-a`: Releases the 'A' key.
- `rel-d`: Releases the 'D' key.
- `rel-space`: Releases the 'Space' key.
- `rel-ctrl`: Releases the 'Ctrl' key.

---

For the `key` keyword, users can send messages like `key-e` to simulate pressing and holding the 'E' key, and `rel-e` to release the 'E' key. Here are the updated examples:

- `key-e`: Simulates pressing and holding the 'E' key.
- `key-f`: Simulates pressing and holding the 'F' key.
- `key-g`: Simulates pressing and holding the 'G' key.
- `rel-e`: Releases the 'E' key.
- `rel-f`: Releases the 'F' key.
- `rel-g`: Releases the 'G' key.

These examples allow users to control additional keys on the keyboard using the `key` and `rel` keywords in the YouTube chat. Adjust the key names as needed for your specific use case.
