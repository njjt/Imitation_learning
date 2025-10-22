# Imitation Learning
The simulation code is based on Windows 11, simulation using Genesis 0.3.4. WSL2 Ubuntu 24.04.1.

If WSL meets problems with screen requests, add these lines to your `~/.bashrc`:

```bash
# Enable display and sound for WSLg
echo 'export DISPLAY=:0' >> ~/.bashrc
echo 'export WAYLAND_DISPLAY=wayland-0' >> ~/.bashrc
echo 'export PULSE_SERVER=/mnt/wslg/PulseServer' >> ~/.bashrc

