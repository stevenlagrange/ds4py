# ds4py

## Dependencies
- Python 3 Development Version: https://www.python.org/downloads/
- pygame: https://www.pygame.org/news

## Connecting the Dualshock 4 Controller to a RaspberryPi:
1. Run the Dualshock 4 Driver Utility Setup.
```bash
chmod +x setup.sh
setup_pi.sh
```
2. Next start ds4drv:
```bash
sudo ds4drv
```
As daemon:
```bash
sudo ds4drv &
```
3. Pair bluetooth controller to the device.
