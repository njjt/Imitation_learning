# Imitation Learning

If WSL meets problems with screen requests, add these lines to your `~/.bashrc`:

```bash
# Enable display and sound for WSLg
echo 'export DISPLAY=:0' >> ~/.bashrc
echo 'export WAYLAND_DISPLAY=wayland-0' >> ~/.bashrc
echo 'export PULSE_SERVER=/mnt/wslg/PulseServer' >> ~/.bashrc

