<!--
SPDX-FileCopyrightText: 2026 Department of Decentralization
SPDX-License-Identifier: CC-BY-SA-4.0
-->

# ethberlin-2-photos

Photos from ETHBerlin ZWEI, August 21-25, 2019.

Conference photos by [Anton Tal](https://www.antontal.com/), weekend photographer unknown.
Licensed [CC BY-SA 4.0](LICENSE).

- `conference-1-001.jpg` to `conference-1-075.jpg`: conference day 1, Wednesday, August 21, 2019, 75 photos.
- `conference-2-001.jpg` to `conference-2-075.jpg`: conference day 2, Thursday, August 22, 2019, 75 photos.
- `weekend-1-001.jpg` to `weekend-1-038.jpg`: weekend day 1, Friday, August 23, 2019, 38 photos.
- `weekend-2-001.jpg` to `weekend-2-082.jpg`: weekend day 2, Sunday, August 25, 2019, 82 photos.
- Order in `images.json`: file name order, capture time within each day.
- Anton Tal's conference albums: [day 1](https://www.picdrop.com/antontalphotography/BANqhinj1H), [day 2](https://www.picdrop.com/antontalphotography/kG2K5tqDXc).
- Conference photos: unchanged.
- Weekend photos: 2250 px, from the camera files in commit `cee5607`:

```sh
vipsthumbnail IMG_8508.JPG --size 2250 -o 'weekend-1-001.jpg[Q=85]'
```

- Thumbnails, 300 px high:

```sh
vipsthumbnail conference-1-001.jpg --size x300 -o 'thumbnails/%s.jpg[Q=80,strip]'
```
