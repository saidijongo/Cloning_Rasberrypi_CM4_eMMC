# Cloning_Rasberrypi_CM4_eMMC
Cloning two raspberry pi CM4s

sudo dd if=/dev/sdX of=cm4_isanim.img bs=4M status=progress
###############
sudo dd if=cm4_isanim.img of=/dev/sdY bs=4M status=progress
