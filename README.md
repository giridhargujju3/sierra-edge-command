# Sierra Edge Command

SIERRAEDGE LOGIN PAGE — EXACT UI/UX IMPLEMENTATION SPEC

You are working inside my existing SIERRAEDGE application.

Build the login page as a production-quality futuristic command-center

interface.

DO NOT redesign the application from your imagination.

Follow every UI specification below precisely.

============================================================

1. PRODUCT IDENTITY

============================================================

Application:

SIERRAEDGE

Subtitle:

SMART MANNEQUIN SYSTEM

Purpose:

Real-time Smart Mannequin / Soldier Monitoring System.

The login screen must feel like the secure entry point to a professional

mission-control platform.

Design character:

- futuristic

- military/industrial

- technical

- premium

- operational

- secure

- dark

- high-tech HUD

Avoid:

- generic SaaS

- generic healthcare

- gaming UI

- cyberpunk purple/pink

- excessive neon

- glassmorphism-heavy consumer UI

- generic centered login page

============================================================

2. FULL VIEWPORT

============================================================

The UI must completely cover the browser.

Use:

width: 100%;

height: 100vh;

min-height: 100vh;

The body must have:

margin: 0;

overflow: hidden;

No white margins.

No visible browser-background gaps.

No centered max-width wrapper around the entire application.

Everything must extend from the LEFT edge to the RIGHT edge.

============================================================

3. OVERALL COMPOSITION

============================================================

Desktop composition:

------------------------------------------------------------

|                    TOP HEADER                            |

------------------------------------------------------------

|                                                          |

|  LEFT MISSION     DIGITAL COMMAND       LOGIN CONSOLE   |

|  CONTENT          VISUALIZATION                         |

|                                                          |

|  SMART            WORLD MAP / RADAR                     |

|  MANNEQUIN        NETWORK / TERRAIN                     |

|  SYSTEM                                                 |

|                                                          |

|  REAL-TIME                                               |

|  SOLDIER                                                 |

|  MONITORING                                              |

|                                                          |

------------------------------------------------------------

|              FULL WIDTH BOTTOM STATUS BAR                |

------------------------------------------------------------

The screen should feel like ONE unified operational interface.

Do NOT make the left section look like a marketing website

and the right section look like an unrelated login card.

============================================================

4. TOP HEADER

============================================================

Create a full-width top HUD header.

Height:

approximately 58–64px.

The header should have:

- dark translucent navy background

- cyan border

- subtle cyan glow

- technical corner treatment

- slight rounded corners

LEFT:

[SIERRAEDGE LOGO]

SIERRAEDGE

|

SMART MANNEQUIN SYSTEM

SIERRAEDGE should be:

- large

- bold

- cyan

- uppercase

- letter spacing around 2px

SMART MANNEQUIN SYSTEM:

- smaller

- muted white/cyan

- uppercase

- letter spacing around 3px

Use the EXISTING SIERRAEDGE logo if available.

Do not create a new logo if an existing asset exists.

RIGHT:

● LIVE - ESP32 RIG

|

⚠ CRITICAL

|

◷ LAST SYNC 14:40:27

Use:

LIVE = green

ESP32 RIG = cyan

CRITICAL = red

LAST SYNC = muted cyan

Use technical monospace typography.

Header content must have comfortable horizontal padding:

approximately 40–55px.

Do NOT make header text microscopic.

============================================================

5. BACKGROUND

============================================================

The background must be rich.

Do NOT leave large empty dark areas.

Base:

very dark navy/black.

Add a subtle technical grid covering the entire page.

Grid:

- thin

- low opacity

- cyan/teal

- approximately 40–55px spacing

The grid should fade naturally toward some areas.

============================================================

6. DIGITAL WORLD MAP

============================================================

Behind the main content, create a large digital world map.

Position:

center-left.

It should occupy approximately:

50–60% of the main content width.

Use:

- tiny cyan dots

- small network points

- faint geographic outlines

- connected lines

- subtle glowing nodes

Opacity:

approximately 10–25%.

The world map should be clearly visible,

but must remain behind the UI.

It should look like a military/digital operations map.

Do NOT use a photographic map.

============================================================

7. CENTER RADAR

============================================================

Place a large radar visualization in the center-left.

Approximate position:

x = 44–47% viewport width

y = 48–52% viewport height

Size:

approximately 360–450px diameter on 1920×1080.

Create:

- 5–7 concentric circles

- horizontal crosshair

- vertical crosshair

- center point

- small surrounding points

- subtle radial lines

The radar must be clearly visible.

Use thin cyan lines.

Opacity:

approximately 25–50%.

Center point:

cyan glow.

============================================================

8. RADAR ANIMATION

============================================================

Add a slow scanning animation.

Use a rotating radar scan line.

Duration:

approximately 5–8 seconds.

Loop continuously.

Also:

- center point subtly pulses

- occasional network point activates

Animation must be smooth and subtle.

No aggressive flashing.

============================================================

9. LEFT MISSION CONTENT

============================================================

Position:

left approximately 50–65px.

Top:

approximately 150–180px.

Width:

approximately 340–420px.

At the top:

MISSION READY

Use:

cyan

monospace

uppercase

small text

letter spacing 3px

Add a thin cyan line extending to the right.

============================================================

10. MAIN LEFT TITLE

============================================================

Display exactly:

SMART

MANNEQUIN

SYSTEM

Three lines.

Use a strong condensed/futuristic sans-serif font.

Recommended:

Space Grotesk

Inter

Rajdhani

IBM Plex Sans

If an existing project font is already used,

reuse it where appropriate.

Desktop size:

approximately 50–58px.

Weight:

700–800.

Color:

#EAF8FC.

Line-height:

approximately 0.95–1.0.

Letter spacing:

1–2px.

This should be large and visually dominant.

============================================================

11. SECONDARY LEFT TITLE

============================================================

Below the main title:

REAL-TIME

SOLDIER

MONITORING

Three lines.

Color:

bright cyan.

Font size:

approximately 28–36px.

Weight:

600–700.

Letter spacing:

approximately 3–5px.

Line height:

approximately 1.1.

This is an important visual element.

============================================================

12. LEFT DESCRIPTION

============================================================

Below:

Secure, intelligent, and real-time monitoring

for training, research, and operational readiness

through a unified digital platform.

Use:

font size: 14–16px

line-height: 1.5–1.6

color: #A0B6BF

Maximum width:

approximately 400px.

Do not make the description too small.

============================================================

13. LEFT LOWER TAGLINE

============================================================

Display:

REAL PEOPLE

SAFER MISSIONS

A MORE SECURE TOMORROW

Use:

cyan

monospace

uppercase

11–13px

letter-spacing: 2–3px

Position it below the description.

============================================================

14. COORDINATE HUD

============================================================

Add small technical coordinate readouts around the world map/radar.

Example:

34.0522° N

118.2437° W

Another:

1.3521° N

103.8198° E

Use small monospace text.

Color:

cyan.

Opacity:

approximately 60–80%.

These are decorative HUD elements.

Do not imply they are the user's actual location.

============================================================

15. NETWORK GRAPHICS

============================================================

Add subtle network paths around the radar.

Use:

- small nodes

- thin curved paths

- straight technical paths

- glowing connection points

Keep them behind the main UI.

Do not make the network too dense.

============================================================

16. BOTTOM WIRE-FRAME MOUNTAINS

============================================================

THIS IS REQUIRED.

Create a prominent futuristic wireframe mountain/terrain landscape

across the bottom-left and center area.

The terrain should begin at the LEFT edge.

It should extend across the lower portion of the page toward the

login panel.

Use:

- wireframe triangular terrain

- perspective grid

- cyan outlines

- glowing vertices

- subtle horizontal scan lines

The mountains should look like a digital terrain scan.

Height:

approximately 150–190px.

Position:

bottom of main content, directly above the footer.

Opacity:

approximately 25–45%.

It must be clearly visible.

Do NOT make it almost invisible.

Do NOT remove the mountain graphics.

Do NOT use a photographic mountain.

============================================================

17. TERRAIN ANIMATION

============================================================

Add subtle animation:

- glowing vertices pulse slowly

- occasional scanning light

- subtle moving data point

Keep it slow.

============================================================

18. RIGHT LOGIN CONSOLE

============================================================

The login panel is the primary interactive element.

Position:

right: approximately 3.5–5%.

top: approximately 8–10%.

Width:

approximately 34–36vw.

Maximum width:

approximately 610–630px.

Minimum desktop width:

approximately 500px.

Height:

approximately 72–78vh.

It should be large.

Do NOT make it a small floating card.

============================================================

19. LOGIN PANEL STYLE

============================================================

Background:

rgba(3, 20, 28, 0.92)

Use:

backdrop-filter: blur(10–14px)

Border:

1px solid rgba(0, 217, 255, 0.45)

Outer glow:

subtle cyan.

Example:

0 0 30px rgba(0, 217, 255, 0.08)

Do not over-glow.

============================================================

20. LOGIN PANEL CORNERS

============================================================

Use technical HUD corners.

Each corner should have:

- cyan line extension

- angled/bracket appearance

- brighter corner highlight

Top-left

Top-right

Bottom-left

Bottom-right

The corner treatment should visually resemble a futuristic

command console.

============================================================

21. LOGIN PANEL PADDING

============================================================

This is important.

Use generous padding.

Desktop:

approximately 38–48px.

Content must NOT touch the border.

Horizontal content width should remain comfortable.

============================================================

22. LOGIN BRANDING

============================================================

At the top center:

SIERRAEDGE logo

SIERRAEDGE

SMART MANNEQUIN SYSTEM

Use the existing logo asset.

Logo:

approximately 55–75px.

SIERRAEDGE:

approximately 24–28px.

Subtitle:

approximately 9–11px.

Center align.

============================================================

23. WELCOME

============================================================

Display:

WELCOME BACK

Font:

26–32px.

Weight:

700.

Letter spacing:

2–4px.

Color:

white.

Below:

Secure access to your

mannequin monitoring workspace.

Font:

14–16px.

Color:

#91A9B3.

Center align.

============================================================

24. LOGIN FORM

============================================================

USERNAME FIELD:

Username / Email

PASSWORD FIELD:

Password

Inputs:

width: 100%

height: 52–56px

border-radius: 8–10px

dark transparent background

cyan border

Use icons.

Username:

user icon

Password:

lock icon

Password:

eye icon on right.

============================================================

25. INPUT INTERACTION

============================================================

Normal:

subtle cyan border.

Hover:

slightly brighter border.

Focus:

bright cyan border

subtle cyan glow.

Transition:

150–250ms.

============================================================

26. REMEMBER / FORGOT

============================================================

Single row.

LEFT:

☑ Remember me

RIGHT:

Forgot password?

Font:

12–14px.

Forgot password should be cyan.

============================================================

27. LOGIN BUTTON

============================================================

Full width.

Height:

52–56px.

Text:

Login →

Use cyan/green gradient:

green/cyan.

Example:

linear-gradient(

90deg,

#42E6A8,

#00D9FF

)

Text:

dark navy.

Font:

15–17px.

Weight:

700.

============================================================

28. LOGIN BUTTON ANIMATION

============================================================

Hover:

- subtle glow

- gradient brightness increases

- arrow shifts 3–5px right

Active:

scale 0.98.

Transition:

150–200ms.

============================================================

29. OR DIVIDER

============================================================

Below login button:

horizontal line

OR

horizontal line

Use:

muted cyan/gray.

Keep it clean.

============================================================

30. SSO BUTTON

============================================================

Text:

Sign in with SSO

Full width.

Height:

approximately 50–54px.

Outlined cyan border.

Transparent dark background.

Use building/SSO icon.

Hover:

subtle cyan glow.

If SSO functionality already exists,

connect to it.

============================================================

31. SECURITY FOOTER INSIDE LOGIN

============================================================

Add divider.

Then:

shield icon

SECURE CONNECTION

ENCRYPTED | AUTHORIZED ACCESS | LIVE SYSTEM

SECURE CONNECTION:

green/cyan.

Use small technical monospace text.

This should sit near the bottom of the login console.

============================================================

32. LOGIN PANEL VERTICAL LAYOUT

============================================================

Use approximately:

logo

↓

18–22px

welcome

↓

10–14px

description

↓

30–35px

username

↓

12px

password

↓

12px

remember/forgot

↓

18–20px

login

↓

18–22px

OR

↓

18–20px

SSO

↓

25–35px

security section

Do NOT leave a huge empty area inside the login panel.

============================================================

33. NO SENSOR DATA

============================================================

Absolutely NO sensor visualization on this login page.

Do NOT show:

SHOCK

TEMPERATURE

ACOUSTIC

CO

444 ppm

37°C

34 dB

CLEAR

Forehead

Chest

Ear

Arm

Those belong to the dashboard.

============================================================

34. NO MANNEQUIN

============================================================

Absolutely NO:

3D mannequin

human body

human figure

digital human

sensor body

The login page uses ABSTRACT command visualization only.

============================================================

35. BOTTOM STATUS BAR

============================================================

Create a FULL-WIDTH bottom operational navigation bar.

It must stretch:

LEFT EDGE

------------------------------

RIGHT EDGE

Height:

approximately 75–82px.

Do NOT place it only under the left section.

Do NOT use a narrow centered container.

============================================================

36. BOTTOM BAR STRUCTURE

============================================================

Use five logical areas:

1. REAL-TIME SENSOR DATA

2. DIGITAL TWIN

3. MISSION MONITORING

4. SYSTEM STATUS

5. BUILT FOR A SAFER TOMORROW

The first four should occupy the majority of the width.

The fifth message should sit on the far right.

============================================================

37. FOOTER DISTRIBUTION

============================================================

Use full-width grid/flex.

Example:

25% | 20% | 20% | 20% | 15%

or another balanced distribution.

Do NOT cluster all four navigation items on the left.

The footer should visually occupy the entire width.

============================================================

38. FOOTER ITEM 1

============================================================

Icon:

waveform / pulse

Text:

REAL-TIME

SENSOR DATA

============================================================

39. FOOTER ITEM 2

============================================================

Icon:

cube

Text:

DIGITAL

TWIN

============================================================

40. FOOTER ITEM 3

============================================================

Icon:

target / crosshair

Text:

MISSION

MONITORING

============================================================

41. FOOTER ITEM 4

============================================================

Icon:

bar chart / system status

Text:

SYSTEM

STATUS

============================================================

42. FOOTER ITEM 5

============================================================

Far right:

BUILT FOR A SAFER TOMORROW

Use:

cyan

monospace

uppercase

11–13px.

============================================================

43. FOOTER ICONS

============================================================

Use existing icon library if already installed.

Icons:

24–30px.

Color:

cyan.

Style:

thin line icons.

Do not install another icon library unless necessary.

============================================================

44. FOOTER DIVIDERS

============================================================

Use vertical dividers between the four navigation sections.

Color:

rgba(0, 217, 255, 0.25).

Thin.

Clean.

============================================================

45. FOOTER HOVER

============================================================

On hover:

- icon glow

- text becomes slightly brighter

- subtle background highlight

No large movement.

============================================================

46. TYPOGRAPHY

============================================================

Use a professional modern font.

Preferred:

Inter

Space Grotesk

Rajdhani

Technical metadata:

JetBrains Mono

IBM Plex Mono

Use technical monospace only for:

- status

- coordinates

- labels

- footer metadata

- security text

- system information

Do not make every sentence monospace.

============================================================

47. FONT HIERARCHY

============================================================

Header:

18–24px branding.

Main title:

50–58px.

Secondary title:

28–36px.

Description:

14–16px.

Login heading:

26–32px.

Input text:

14–16px.

Button:

15–17px.

Footer:

11–14px.

Technical labels:

10–13px.

Do NOT make the entire UI microscopic.

============================================================

48. BORDER STYLE

============================================================

Use a consistent HUD border language.

Thin cyan lines.

Small technical corner accents.

Subtle glow.

Dark transparent surfaces.

Avoid thick rectangular borders.

============================================================

49. VISUAL DEPTH

============================================================

Create 3 visual layers:

LAYER 1:

background grid / world map

LAYER 2:

radar / network / terrain

LAYER 3:

actual UI

The login panel must always remain readable above the background.

============================================================

50. ANIMATION SYSTEM

============================================================

Page load:

Header:

fade in.

Mission content:

fade + slide upward.

World map:

fade in.

Radar:

fade + scan.

Login panel:

fade + translateY(12px).

Terrain:

fade in.

Duration:

500–900ms.

============================================================

51. BACKGROUND ANIMATION

============================================================

Slow:

radar scanning

network node pulse

data point glow

terrain point pulse

subtle scan line

Do not continuously animate everything.

The interface should feel alive but professional.

============================================================

52. RESPONSIVE

============================================================

Desktop is PRIMARY.

At:

1920×1080

1600×900

1440×900

1366×768

everything should remain balanced.

At tablet:

collapse the left/center layout appropriately.

At mobile:

single-column layout.

Login panel becomes the primary content.

Background graphics remain subtle.

No horizontal scrolling.

============================================================

53. MOBILE FOOTER

============================================================

On mobile:

convert bottom navigation to a 2×2 or compact responsive layout.

Do not allow the footer to overflow.

Safety message can move below navigation items.

============================================================

54. ACCESSIBILITY

============================================================

Use semantic HTML.

Use:

form

label

input

button

Keyboard navigation.

Visible focus states.

Enter submits login.

Password eye toggle is keyboard accessible.

Remember checkbox is accessible.

============================================================

55. AUTHENTICATION

============================================================

Do NOT create fake authentication.

Inspect the existing project first.

Find:

- existing login API

- auth service

- session handling

- token management

- route protection

- dashboard route

Reuse existing authentication.

Do not create a second authentication system.

============================================================

56. LOGIN STATES

============================================================

Default:

Login

Loading:

AUTHENTICATING...

Error:

AUTHENTICATION FAILED

Success:

AUTHENTICATION VERIFIED

SYSTEM ACCESS GRANTED

Then navigate to the existing dashboard.

============================================================

57. PASSWORD

============================================================

Password visibility toggle must work.

Use:

password

and

text

types.

============================================================

58. REMEMBER ME

============================================================

Use the existing application's remember/session behavior if available.

Do not store passwords.

============================================================

59. FORGOT PASSWORD

============================================================

Reuse existing forgot-password flow.

Do not invent backend APIs.

============================================================

60. SSO

============================================================

Reuse existing SSO flow if available.

Do not fake SSO functionality.

============================================================

61. PERFORMANCE

============================================================

Keep the page lightweight.

Prefer:

CSS animation

SVG

CSS gradients

requestAnimationFrame only when necessary.

Avoid heavy videos.

Avoid massive background images.

Avoid unnecessary packages.

============================================================

62. EXISTING ASSETS

============================================================

Inspect:

public/

src/images/

src/assets/

Reuse:

existing SIERRAEDGE logo

existing icons

existing fonts

existing design tokens

Do not create duplicate assets unnecessarily.

============================================================

63. IMPLEMENTATION ARCHITECTURE

============================================================

Keep the code maintainable.

Suggested conceptual structure:

LoginPage

├── TopHeader

│

├── BackgroundCommandLayer

│   ├── Grid

│   ├── WorldMap

│   ├── Radar

│   ├── Network

│   ├── Coordinates

│   └── Terrain

│

├── MissionContent

│

├── LoginConsole

│   ├── Brand

│   ├── Welcome

│   ├── LoginForm

│   ├── LoginButton

│   ├── SSO

│   └── Security

│

└── BottomStatusBar

Adapt this to the existing project architecture.

============================================================

64. IMPORTANT LAYOUT RULE

============================================================

Do NOT solve layout problems by making everything smaller.

If something does not fit:

first adjust:

- spacing

- container width

- positioning

- responsive sizing

Only then adjust font sizes.

The final page must remain readable.

============================================================

65. IMPORTANT BACKGROUND RULE

============================================================

The page must NOT have a large empty center.

The center should contain:

WORLD MAP

+

RADAR

+

NETWORK

+

GRID

+

TERRAIN

All subtle but visible.

============================================================

66. IMPORTANT FOOTER RULE

============================================================

The bottom bar must occupy the FULL WIDTH.

It must begin at:

x = 0

and end at:

x = 100%.

The navigation items must be distributed across the width.

Do NOT leave the right half empty.

============================================================

67. IMPORTANT LOGIN RULE

============================================================

The login console must have:

- enough width

- enough padding

- readable text

- large inputs

- large Login button

- visible SSO

- visible security section

Do not make the login form tiny.

============================================================

68. IMPORTANT HEADER RULE

============================================================

The header must be readable.

Do not reduce:

SIERRAEDGE

SMART MANNEQUIN SYSTEM

LIVE

ESP32 RIG

CRITICAL

LAST SYNC

to tiny unreadable text.

============================================================

69. IMPORTANT TERRAIN RULE

============================================================

The wireframe mountain landscape is REQUIRED.

It should be clearly visible along the bottom-left/center.

It must not disappear into the background.

============================================================

70. FINAL VISUAL HIERARCHY

============================================================

The final screen should visually read:

SIERRAEDGE

↓

SMART MANNEQUIN SYSTEM

↓

MISSION / SOLDIER MONITORING

↓

DIGITAL COMMAND ENVIRONMENT

↓

SECURE LOGIN CONSOLE

↓

FULL-WIDTH SYSTEM STATUS BAR

============================================================

71. FINAL QUALITY CHECK

============================================================

After implementation:

RUN THE APPLICATION.

Test at:

1920×1080

1600×900

1440×900

1366×768

Verify:

[ ] entire viewport covered

[ ] header full width

[ ] header readable

[ ] SIERRAEDGE branding correct

[ ] world map visible

[ ] radar visible

[ ] radar animated subtly

[ ] network graphics visible

[ ] wireframe mountains clearly visible

[ ] left title readable

[ ] left mission title readable

[ ] description readable

[ ] login panel large

[ ] login panel properly padded

[ ] login panel right aligned

[ ] username input large enough

[ ] password input large enough

[ ] password visibility works

[ ] Remember me works

[ ] Forgot Password uses existing flow

[ ] Login uses existing authentication

[ ] SSO uses existing flow

[ ] Security section visible

[ ] NO mannequin

[ ] NO 3D

[ ] NO sensor cards

[ ] NO sensor values

[ ] footer starts at left edge

[ ] footer reaches right edge

[ ] footer navigation distributed across width

[ ] footer icons visible

[ ] footer safety message visible

[ ] no horizontal scrolling

[ ] no accidental vertical scrolling

[ ] dashboard remains unchanged

============================================================

72. FINAL INSTRUCTION

============================================================

Do not just make the page "similar."

Implement the complete visual system described above.

The most important visual characteristics are:

FULL-SCREEN HUD

+

DARK NAVY BACKGROUND

+

DIGITAL WORLD MAP

+

LARGE CYAN RADAR

+

NETWORK GRAPHICS

+

VISIBLE WIREFRAME MOUNTAINS

+

LARGE RIGHT LOGIN CONSOLE

+

STRONG SIERRAEDGE TYPOGRAPHY

+

FULL-WIDTH BOTTOM STATUS BAR

The final result must feel like a real:

SIERRAEDGE SMART MANNEQUIN SYSTEM

SECURE COMMAND ACCESS

interface.

Do not modify the existing dashboard or backend.

Implement, run, inspect, correct spacing/alignment issues,

and verify the final responsive result.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/49a92b25-e595-4ddf-b890-7b0236d882ba).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
