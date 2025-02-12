# Webtop Images with MEGA Download Links

## Available Images

| Image | Download Link |
|--------|--------------|
| webtop-debian-kde.tar | [📥 Download](https://mega.nz/file/qnBzUDLa#kC1xLncy6cRGjNBNHwMzk9uNbOV8a4aX5LIOXFO4PfA) 📋 |
| webtop-debian-mate.tar | [📥 Download](https://mega.nz/file/zyI1DRJA#qizKe2rcW7N19mvfusBTJKbXZW39QgwX2ux0gg70Lrs) 📋 |
| webtop-debian-xfce.tar | [📥 Download](https://mega.nz/file/r3xQ0SCD#n8ZzTIaVtpY71QtSTDzvQ2y3Cgk9XXgPeKRdZ0v0t3M) 📋 |
| webtop-ubuntu-kde.tar | [📥 Download](https://mega.nz/file/niJAGaKa#B3R_nnJ1IDk1f_Nm7reeSUyvt-d5k1WcFlrWfDU6vTA) 📋 |
| webtop-ubuntu-kde.tar | [📥 Download](https://mega.nz/file/7yAxxaIY#MT2AxomjNbuHIhSy-epL6x8M6HUHH5_n1t5g-W4u2eA) 📋 |
| webtop-ubuntu-xfce.tar | [📥 Download](https://mega.nz/file/v34nxaaK#cKp8A66IwlaDKBBvOnMPTESjYOyZ6DgVmxIeB0-FblA) 📋 |

## Installation Instructions

### Step 1: Install MEGATools
```bash
sudo apt install megatools -y
```

### Step 2: Download the Image
Replace `<link>` with the actual download link from the table above.
```bash
megadl <link>
```

### Step 3: Load the Image with Docker
Replace `<downloaded image path>` with the path to the downloaded `.tar` file.
```bash
docker load -i <downloaded image path>
```

