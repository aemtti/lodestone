# Lodestone

Iron filings on a sheet of paper, for a phone.

**→ https://aemtti.github.io/lodestone/**

Rest a finger on the paper and a magnet appears beneath it. Tap the paper (or knock the phone) and the filings jump and settle along the field. Two fingers make two poles. Tilt to pour, twist to swirl. With no magnet near, a tap lets them lie down toward the real magnetic north, read from the phone's compass.

Everything (image, light, sound) is generated in code in a single `index.html`. No libraries, no assets.

Sensors used: device orientation (absolute when available, for north and the light), device motion (knocks, gyroscope twist), touch contact size (magnet strength), vibration, Web Audio, screen wake lock.

On a desktop: move the mouse to catch the light, click to tap, hold to place a magnet, right-click to leave one, arrow keys tilt, scroll twists, space knocks.

종이 위의 쇳가루. 손가락을 대면 그 아래에 자석이 생기고, 종이를 두드리면 쇳가루가 자기력선을 따라 늘어섭니다.
