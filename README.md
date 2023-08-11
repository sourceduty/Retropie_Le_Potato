# Retropie_Le_Potato

📃 How to Install RetroPie on Le Potato Libre Computer Board (AML-S905X-CC)

![Le-Potato](https://github.com/sourceduty/Retropie_Le_Potato/assets/123030236/b8224cd1-d865-43ce-9bb9-11d5cc39b233)

## Step 1:

Download belenaEtcher from: https://www.balena.io/etcher

Download image file from:
http://share.loverpi.com/board/libre-computer-project/libre-computer-board-aml-s905x-cc/image/retropie/

Format your SD card and use belenaEtcher to write the image file to the SD card.

## Step 2:

Hook up the Libre board to ethernet, power and then run:
sudo apt install rapidjson-dev

Wait for this to install for 2 minutes and then install emulationstation:
sudo ~/RetroPie-Setup/retropie_setup.sh

Go to: Manage Packages > Manage core packages > Emulationstation > Install from source
This will take 20 minutes to install.

Reboot after install from the emulationstation menu.
Power off and remove the ethernet cable.

## Step 3:

Insert wired USB controller and power on the board.
Configure the controller.
Power off the board.

## Step 4:

Copy game ROM files to a folder named "retropie" on a USB thumb drive.
Organize game ROM files into system folders like NES, SNES and N64.
Insert the USB thumb drive into the Libre board and power it on.
Wait for 2 minutes while the games are copied.
Power off the Libre board and remove the USB thumb drive.

## Step 5:

Power on the Libre board and play RetroPie emulated games.

## Notes:

- Press the Hotkey (recommend setting it as Select) and Start buttons simultaneously to quit any game.
