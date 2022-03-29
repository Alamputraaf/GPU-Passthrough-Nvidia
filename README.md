# GPU-Passthrough-Nvidia-Optimus
This is guide for Laptop with Hybrid-Graphics
# DO IT AT YOUR OWN RISK, I AM NOT RESPONSIBLE FOR ANY DAMAGE TO YOUR HARDWARE

Hello,
Im sorry for my bad english xd, im still learning more and more for conversation :)
This is my first Project of Passing my Nvidia GPU to QEMU KVM Windows 11 with Hybrid Graphics.
Hopefully my Guide can be understanding for you guys

---------------------------------------------------------------------------------------------------------------------
Im using Lenovo Legion 5 (ARH05) 2020
CPU: Ryzen 5 4600H (6c/12t)
RAM: 16 GB DDR4-3200 Mhz
SSD: 512 GB
GPU: AMD Integrated Graphics (for Linux) Nvidia GTX 1650 GDDR6 (for Windows 11)
OS: Manjaro Qonos 21.2.5 KDE Version with Nvidia Proprietary Driver
Kernel:5.15.28-1 Manjaro
---------------------------------------------------------------------------------------------------------------------

# DISVANTAGES
1. My Audio on my Windows 11 QEMU KVM is not working for now
2. Draining Battery Issue (except people installing OPTIMUS MANAGER)
3. This tutorial mostly with Manjaro OS, i don't know any other OS can make it possible.
4. For now is working for Second Screen (VIA HDMI to SMART TV), im still learning how to connect with Looking Glass

Previously, I had tried using the Single GPU-Passthorugh from Mutahar tutorial and many youtubers on the internet with hooks helper script, but it always ended up kicking me into the SDDM login again and again. And ended up with Hybrid Graphics for now.

This Project thanks a lot to My Favorite Youtuber 'Mutahar' @Someordinarygamers, Reddit Community R/VFIO and many more in documentation.
