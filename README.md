##⚡ Jarvis Widgets & Custom CSS Studio

#Welcome to the documentation and guide for Jarvis Widgets—the modular, glassmorphic widget system built for the Jarvis HOME ambient display.

#🧩 Built-in Widget Library

Jarvis HOME comes with 7 pre-configured ambient widgets that can be assigned to any of the 3 bottom dashboard slots:

# First Period (nextClass)

Automatically calculates today's schedule (or tomorrow's preview after school hours) and displays your upcoming or current class.

Interactive: Clicking the widget triggers a cozy English voice readout of your schedule.

# Weather Display (weather)

Renders current temperature, atmospheric conditions, and location.

# Focus Timer (timer)

A built-in 25-minute Pomodoro focus timer with interactive start and pause controls.

# Music Launcher (music)

Quick launcher for ambient lo-fi chimes and soundscapes. Clicking it instantly toggles playback and reveals the Now Playing card.

# Daily Recap (recap)

Displays your daily priorities and checklist items.

# Quote of the Day (quote)

Cycles through inspirational quotes with each click.

# Empty Slot (empty)

Clean placeholder indicating an available slot ready for customization or custom CSS injection.

## 🎨 Custom CSS Widget Studio

The Custom CSS Widget Studio allows you to design, write, and inject custom-styled HTML and CSS widgets directly into any slot on your home screen without restarting or rebuilding the app.

How to Create a Custom CSS Widget:

Open SETTINGS on your Jarvis HOME dashboard.

Click on 🎨 CUSTOM CSS WIDGETS.

Fill out the editor form:

Widget Name: A descriptive label for your custom widget.

Custom CSS: Write your CSS classes and styling rules.

Custom HTML: Write the markup structure of your widget.

Click + SAVE CUSTOM CSS WIDGET.

Click PIN TO WIDGET to instantly mount your bespoke widget onto your dashboard!

## Example Custom CSS Snippet:

.my-custom-card {
  background: linear-gradient(135deg, rgba(253,224,71,0.18), rgba(16,22,16,0.85));
  border: 1px solid #FDE047;
  border-radius: 18px;
  padding: 16px;
  text-align: center;
  box-shadow: 0 8px 24px rgba(0,0,0,0.5);
}
.my-custom-title {
  color: #FDE047;
  font-weight: 800;
  font-size: 13px;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}


## Example Custom HTML Snippet:

<div class="my-custom-card">
  <div class="my-custom-title">⚡ SYSTEM STATUS</div>
  <p style="font-size: 11px; color: #fff; margin-top: 6px;">All green • Neural link active</p>
</div>
