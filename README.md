# Shadowfetch-LinuxShadowFetch Linux

The Snap-Free KDE Distro You Actually Want to Use.Built on Ubuntu. Powered by Flatpak. Styled by rebels.

🚀 What is ShadowFetch?

ShadowFetch is a custom Ubuntu-based Linux distribution focused on simplicity, speed, and full control. We’ve removed Snap entirely, added full Flatpak support with Flathub out of the box, and wrapped it all in the beauty and power of KDE Plasma.

Key Features:

💥 No Snap — Snapd is completely removed.

🧩 Flatpak-First — Comes preinstalled with Flatpak and Flathub support.

🎨 KDE Plasma Desktop — Lightweight, modern, and insanely customizable.

🔧 Custom Scripts & Terminal Tools — Includes our shadowfetch system info tool.

🧼 Bloat-Free — Minimal, fast, and lean.

📦 Default Apps

Category

App (via Flatpak)

Web Browser

Firefox

File Manager

Dolphin

Text Editor

Kate

Terminal

Konsole

Software Store

Discover + Flathub

Extras

VLC, KCalc, Spectacle

🧪 Live ISO and Installation

Coming soon! You'll be able to:

Download the latest ISO

Flash it to a USB stick

Boot into a live session

Install with Calamares installer

💬 Get Involved

We’re building a community around ShadowFetch. Want to:

Suggest apps?

Report bugs?

Contribute themes or scripts?

Just hang out with fellow Snap-free Linux lovers?

👉 Join our Discord (coming soon) or open an issue right here.

🤖 Quick Setup (For the Brave DIY Installer)

While we finish polishing our first ISO, here’s how to turn Kubuntu into ShadowFetch manually:

sudo snap remove firefox
sudo apt purge snapd
sudo apt install flatpak kde-standard gnome-software-plugin-flatpak
sudo flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
flatpak install flathub org.mozilla.firefox

Boom. You’re in ShadowFetch territory.

🧙 About the Project

ShadowFetch is built by Linux nerds who love customization, speed, and software freedom. We wanted something snappy — but not Snap-y.

Stay tuned. The shadow is rising.

⚡ License

Open source. MIT. Fork it, remix it, share it. Just don’t put Snap back in. 😉

