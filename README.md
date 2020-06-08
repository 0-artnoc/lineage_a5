# Roomservice for HTC Desire 816 (LineageOS 14.1)
This File adds the device-specific Repositorys to build LineageOS 14.1

## How to use?
1. Open a Terminal and open your build directory, example:
`cd build/cm-14.1`

2. Enter .repo/local_manifests directory and download the roomservice file:
`cd .repo/local_manifests/ && wget -O roomservice.xml https://raw.githubusercontent.com/GG2501YT/lineage_a5/cm-14.1/roomservice.xml`

3. Go back to your build directory and download the repositorys:
`cd ../../ && repo sync`

Done! Now you can start building LineageOS for your HTC Desire 816 :)
