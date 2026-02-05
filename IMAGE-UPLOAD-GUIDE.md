# Image Upload Guide for HDPM Carousels

This repository structure is ready - only the image files need to be uploaded to complete the package.

## 📸 Image Files Location

All 20 carousel images are available in your **Nebula workspace** under the `images/` folder.

## 🎯 Quick Upload Methods

### Method 1: Download & Upload via GitHub Web UI (Easiest)

1. **Download images from Nebula:**
   - Go to https://nebula.gg
   - Navigate to Files → images folder
   - Download all 20 generated images (generated_*.png and generated_*.jpeg files)

2. **Upload to GitHub:**
   - Visit https://github.com/bramscher/hdpm-instagram-carousels
   - Click "Add file" → "Upload files"
   - Drag and drop images into their respective folders (see mapping below)

### Method 2: Git Clone & Push (For Developers)

```bash
# Clone the repository
git clone https://github.com/bramscher/hdpm-instagram-carousels.git
cd hdpm-instagram-carousels

# Create image directories
mkdir -p images/budget images/premium

# Download images from Nebula to your local machine
# Then copy them to the appropriate folders using the mapping below

# Commit and push
git add images/
git commit -m "Add all carousel images"
git push origin main
```

### Method 3: GitHub API Script (Advanced)

Use the provided Python script in this repository to batch upload via GitHub API.

## 📋 File Mapping

### Budget Property Images (images/budget/)

| Nebula Filename | GitHub Path | Description |
|---|---|---|
| generated_c121c5ee.png | images/budget/01-hero.png | Hero slide with property exterior |
| generated_6d1d0d7d.jpeg | images/budget/02-kitchen.jpeg | Modern kitchen with appliances |
| generated_1ea88d01.jpeg | images/budget/03-living.jpeg | Living room space |
| generated_1c8a95ed.jpeg | images/budget/04-bedroom.jpeg | Bedroom view |
| generated_c239114c.png | images/budget/05-bathroom.png | Full bathroom |
| generated_04ddc36a.png | images/budget/06-features.png | Features grid infographic |
| generated_fa7c7e34.png | images/budget/07-outdoor.png | Outdoor space |
| generated_580f8776.png | images/budget/08-garage.png | Single car garage |
| generated_0932cb99.png | images/budget/09-agent.png | Leasing agent Leesa |
| generated_515c2c23.jpeg | images/budget/10-cta.jpeg | Call-to-action slide |

### Premium Property Images (images/premium/)

| Nebula Filename | GitHub Path | Description |
|---|---|---|
| generated_57f7e395.jpeg | images/premium/01-hero.jpeg | Luxury home hero slide |
| generated_dab3714b.png | images/premium/02-kitchen.png | Gourmet kitchen |
| generated_7e7cb8dd.jpeg | images/premium/03-living.jpeg | Open concept living |
| generated_eadfe2f6.jpeg | images/premium/04-master-suite.jpeg | Master bedroom suite |
| generated_3e449f0a.jpeg | images/premium/05-master-bath.jpeg | Luxury master bathroom |
| generated_0ce06494.jpeg | images/premium/06-features.jpeg | Premium features grid |
| generated_0a74d56c.jpeg | images/premium/07-bedrooms.jpeg | Additional bedrooms |
| generated_89a67568.jpeg | images/premium/08-garage.jpeg | Two-car garage |
| generated_2c0c8bdb.jpeg | images/premium/09-agent.jpeg | Leasing agent slide |
| generated_d01453d8.png | images/premium/10-cta.png | Luxury CTA slide |

## ✅ Current Repository Status

- ✅ README.md - Complete project overview
- ✅ docs/carousel-presentation.pdf - Full presentation with slide descriptions
- ✅ Repository structure defined
- ⏳ images/budget/ - Ready for 10 image uploads
- ⏳ images/premium/ - Ready for 10 image uploads

## 🚀 Next Steps

1. Choose your preferred upload method above
2. Upload all 20 images using the file mapping table
3. Verify all images appear in the GitHub repository
4. Share the complete repository with your team and Konmashi

## 📞 Need Help?

The images are already generated and stored in your Nebula workspace. You can:
- View them at https://nebula.gg → Files → images
- Download individually or in bulk
- Upload to GitHub using any method above

Once uploaded, the repository will be complete and ready for production use!
