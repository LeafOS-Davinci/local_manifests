# Local Manifest for fast syncing with repo
- Navigate to the repo folder (ROM_FOLDER/.repo/) 
- ```git clone https://github.com/bootleggers-davinci/local_manifests/```
- ```repo sync --current-branch --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j$(nproc --all)```
