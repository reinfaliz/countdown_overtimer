# Countdown Overtimer

Countdown Overtimer is a GUI program that counts down the timer from a specified positive time to a specified negative time. You can configure the program via the `config.txt` file.

This program is generated using Gemini 3.

## config.txt
```
# ===========================
# TIMER CONFIGURATION
# ===========================

# --- Start Time ---
40    # Start Minutes
0     # Start Seconds

# --- Stop Time ---
# The timer will continue counting down until it reaches this negative value.
# Example: 15 mins = -15:00
15    # Stop Minutes
0     # Stop Seconds

# --- Audio Files ---
sound_zero.mp3   # Plays at 00:00
sound_limit.mp3  # Plays at Stop Time
```
