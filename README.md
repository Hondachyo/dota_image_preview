# Onyx Changer preview images

The image library is distributed as a single ZIP in GitHub Releases.

Release: `previews-v1`  
Asset: `onyx-previews-v1.zip`  
Contents: 12,375 numeric PNG preview files.

The launcher downloads this archive once, verifies SHA-256, extracts it into the current user's local cache, and reuses it on subsequent launches. The installed executable remains in `C:\Program Files\Onyx Changer`.

For a new image library, publish a new release and update the launcher image manifest. Keep the existing release available for previously distributed launchers.
