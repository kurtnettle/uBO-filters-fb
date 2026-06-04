<h1>uBlock Origin Filters for Facebook</h1>

uBlock Origin filters to eliminate distractions by block Facebook Stories,Reels and prevent *unwanted* doomscrolling (on both desktop and mobile!).

Short-form video loops like **Facebook Reels** are specifically engineered to hijack your brain's reward center. Understanding how they affect us helps explain why removing them can drastically improve your day-to-day life:

* 🎰 **The Dopamine Loop:** The infinite vertical swipe creates a variable dopamine loop. You keep scrolling just to see if the next video is better.

* ⏳ **Time Thief:** Removing friction disables your brain's natural "stopping cues," making it incredibly easy to accidentally lose hours to a screen.

* 📉 **Attention Fryer:** Rapidly consuming 15-second clips trains your brain to expect instant gratification, destroying your real-world attention span.

* 🧠 **Cognitive Overload & Anxiety:** Processing hundreds of random, unrelated emotional contexts back-to-back — a funny cat video followed by a tragedy, followed by a cooking hack — causes severe emotional fatigue and subconscious anxiety.


## Features

* 🚫 **Blocks Facebook Reels & Stories:** Entirely removes the Stories & Reels tray and individual cards from the top of your feed.
* 🛡️ **Cross-Platform Support:** Works seamlessly across standard desktop (`www.`), mobile (`m.`), and alternative subdomains (`mtouch.`, `web.`).


## Usage

1. Install [uBlock Origin](https://github.com/gorhill/uBlock) extension in your browser
2. Select the features you want to eliminate from your Facebook experience and copy the link (s).

<table align="center">
  <thead>
    <tr>
      <th>Target</th>
      <th>What it blocks</th>
      <th>Raw hosts</th>
    </tr>
  </thead>
  <tbody >
    <tr>
      <td><strong>Reels</strong></td>
      <td>Hide reels icon from the navigation bar and blocks <code>/reels</code> page</td>
      <td align="center">
        <a href="https://raw.githubusercontent.com/kurtnettle/uBO-filters-fb/main/reels.txt">link</a>
      </td>
    </tr>
    <tr>
      <td><strong>Stories</strong></td>
      <td>Removes the horizontal Stories tray and blocks <code>/stories</code> page</td>
      <td align="center">
        <a href="https://raw.githubusercontent.com/kurtnettle/uBO-filters-fb/main/stories.txt">link</a>
      </td>
    </tr>
  </tbody>
</table>

3. Open uBO Dashboard > Filter lists > Import
4. Paste the link(s) and click Apply.


## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.