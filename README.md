**Chat Commands Manual**

You can control the browser using chat commands. Each command starts with a keyword followed by optional parameters. Here's a list of supported keywords and their functionalities:

1. **Keyboard Commands**:
   - **Press Key**: `k,<key>` - Presses the specified key. Example: `k,w` (presses the 'w' key).
   - **Hold Key**: `k,<key> d,<delay>` - Holds the specified key for the given delay in seconds. Example: `k,space d,3` (holds the spacebar for 3 seconds).
   - **Press Multiple Keys**: You can press multiple keys simultaneously by chaining the `k,<key>` commands. Example: `k,w k,space d,3` (presses 'w' and spacebar simultaneously for 3 seconds).

2. **Mouse Movements**:
   - **Move Mouse**: `m,<direction> v,<pixels>` - Moves the mouse in the specified direction by the given number of pixels. Directions: `up`, `down`, `left`, `right`. Example: `m,up v,10` (moves the mouse up by 10 pixels).

3. **Mouse Buttons**:
   - **Click**: `click` - Simulates a left mouse click.
   - **Press Left Mouse Button**: `c,left` - Presses the left mouse button.
   - **Press Right Mouse Button**: `c,right` - Presses the right mouse button.
   - **Hold Mouse Button**: You can hold the mouse button for a specified delay by adding `d,<delay>` at the end. Example: `c,left d,1` (holds the left mouse button for 1 second).

4. **Scroll Wheel**:
   - **Scroll Up**: `w,up v,<amount>` - Scrolls up by the specified amount. Example: `w,up v,3` (scrolls up by 3 units).
   - **Scroll Down**: `w,down v,<amount>` - Scrolls down by the specified amount. Example: `w,down v,3` (scrolls down by 3 units).

5. **Combining Commands**:
   - You can combine multiple commands in a single message. Example: `k,w k,space v,10` (hold down 'w' and spacebar for 10 seconds).

---

Feel free to test these commands in the chat!
