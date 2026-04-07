# Speaking Clock
[https://h-sug1no.github.io/speaking-clock/](https://h-sug1no.github.io/speaking-clock/)

A web-based clock application. By default, it automatically announces the time in English followed by Japanese at specific intervals: every hour at minutes **[0, 7, 15, 22, 30, 37, 45, 52]** and seconds **[0, 30]**.

### The Inspiration
* **Morning Routine:** Designed for those final drifting minutes spent between sleep and wakefulness while listening to music.
* **Time Awareness:** Provides periodic time announcements to help you decide exactly when to finally get out of bed.
    * I originally built a prototype for personal use.
    * This repository was created as an experiment to see how effectively an AI agent could implement the features.
* **Intervals:** The default announcement intervals are values I found most effective through real-world personal use.
* **Bilingual Delivery:** I chose two announcements because once is easy to miss, but three or more felt too repetitive.

---

## Features

* **Bilingual Announcements:** Selectable languages (Default: English → Japanese).
* **Real-time Customization:** Adjustable templates, themes (**Midnight** / **Cyber Matrix** / **Pure White**), and voice settings.
* **Wake Lock:** Keeps the screen on during use.
* **Quick Test:** Instantly preview the announcement settings.

## Usage

1.  Open `index.html` in your browser.
2.  Click **"Start Clock"**.
3.  Customize your experience via the **Settings Panel**.

## Speech Template Variables

* `{h}`: Hour
* `{m}`: Minute
* `{s}`: Second
* `{lts}`: Locale-specific time string

## License

MIT License

---

*This project was enhanced by Gemini, an AI assistant from Google.*
*This project was enhanced by GitHub Copilot.*