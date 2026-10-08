J.A.R.V.I.S - Personal AI Assistant (standalone)
=================================================

HOW TO USE
1. Unzip this folder.
2. Open index.html in Google Chrome (or Edge / Safari).
   - For the microphone to work reliably, it is best to run a tiny local server:
       Windows: double-click start.bat
       Mac/Linux: run  sh start.sh
     then open  http://localhost:8000
   - Without voice, just double-clicking index.html works fine for typing.
3. Click "API key", paste your Anthropic API key (get one at https://console.anthropic.com),
   and press Save. The key is stored only in your browser.
4. Tap the orb and talk, or type your command.

WHAT IT CAN DO
- Voice or text chat in English, Urdu, Hindi, Arabic
- Time/date, calculator, timers, alarms (page must stay open)
- Notes and to-do list (saved in your browser)
- Battery / internet status, dice, coin flip
- Say "switch to red mode" or "change background to matrix"
- Backgrounds: Network, Matrix, Warp, Off
- Hands-free mode and "Jarvis" wake word

NOTES
- Needs an internet connection and an Anthropic API key (API usage is billed by Anthropic).
- Do not share this folder after saving your key in the browser on a shared computer.
- It cannot open apps or control your device beyond what is listed above.
- To change the AI model, edit the MODEL line near the top of the "Claude API" section in index.html.
