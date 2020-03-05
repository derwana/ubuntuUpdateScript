# ubuntu update script
a simple script to update your ubuntu based distro

## 'installation'
1. download file 
2. move it to ``/bin`` directory
3. make executable with ``chmod +x update``

## usage
run from command line with ``sudo`` privileges as ``sudo update``

## what it does
1.  checks your ubuntu version
2. looking for new releases of ubuntu (LTS version)
3. updateing package list
4. upgrading packages
5. removing orphaned packages
6. clearing out the local repository of retrieved package files that can no longer be downloaded
7. update the slocate database
8. check if a reboot is required afterall