# AHFR-Tournoi-HotBox-InstallationPackage

Repository holding the deb package for AHFR-BoardController.

### Prerequisites
  - RaspberryPI 4 (arm/v7 32bits)
  - FullpageOS installed
  - Internet connectivity
  - User `ahfr` created

### Installation steps
  
#### Add the repository

```sh
## As the 'ahfr' user run ...
echo "deb [trusted=yes] https://Association-Hockey-Feminin-Richelieu.github.io/AHFR-Tournoi-HotBox-InstallationPackage/ ./" | sudo tee /etc/apt/sources.list.d/ahfr.list
```

#### Install

```sh
## As the 'ahfr' user run ...
sudo apt update
sudo apt install ahfr-boardcontroller
```


### Conclusion

Once the device has rebooted, you should have the console showing up on the main display.