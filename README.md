# Local Manifest for fast syncing with repo
- Navigate to the repo folder (ROM_FOLDER/.repo/) after doing 
```repo init -u https://github.com/BootleggersROM/manifest.git -b tirimbino```

- ```git clone https://github.com/bootleggers-davinci/local_manifests/```
- ```repo sync --current-branch --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j$(nproc --all)```
