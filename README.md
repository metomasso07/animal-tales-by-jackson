# Animal Tales by Jackson - Website Deployment Guide

## 🎨 What You Have

A complete website with:
- **7 Story Pages** (Stretch, Gary, Penny, Bruno, Al, Finn, Benny)
- Beautiful winter-themed artwork
- Audio player ready for your ElevenLabs recordings
- Mobile-friendly design
- Ready to add Oliver the Owl later

## 📁 Folder Structure

```
animal-tales-by-jackson/
├── index.html           (Homepage with all stories)
├── stretch.html         (Giraffe story)
├── gary.html           (Gecko story)
├── penny.html          (Panda story)
├── bruno.html          (Boar story)
├── al.html             (Alligator story)
├── finn.html           (Fish story)
├── benny.html          (Bee story)
├── images/
│   ├── 1.png          (Gary the Gecko)
│   ├── 2.png          (Penny the Panda)
│   ├── 3.png          (Al the Alligator)
│   ├── 4.png          (Bruno the Boar)
│   ├── 5.png          (Stretch the Giraffe)
│   ├── 6.png          (Benny the Bee)
│   └── 7.png          (Finn the Fish)
└── audio/
    ├── stretch.mp3    (Add your ElevenLabs audio here)
    ├── gary.mp3       (Add your ElevenLabs audio here)
    ├── penny.mp3      (Add your ElevenLabs audio here)
    ├── bruno.mp3      (Add your ElevenLabs audio here)
    ├── al.mp3         (Add your ElevenLabs audio here)
    ├── finn.mp3       (Add your ElevenLabs audio here)
    └── benny.mp3      (Add your ElevenLabs audio here)
```

## 🚀 Deployment Steps

### Step 1: Create GitHub Repository

1. Go to https://github.com/metomasso07Monica
2. Click the **"+" icon** in the top right → **"New repository"**
3. Repository name: `animal-tales-by-jackson`
4. Make it **Public**
5. Do NOT initialize with README (we already have files)
6. Click **"Create repository"**

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface (Easiest)**

1. In your new repository, click **"uploading an existing file"**
2. Drag and drop ALL files and folders from the `animal-tales-by-jackson` folder
3. Make sure the folder structure is preserved
4. Commit the changes

**Option B: Using Git Command Line**

```bash
cd /path/to/animal-tales-by-jackson
git init
git add .
git commit -m "Initial commit - Animal Tales website"
git branch -M main
git remote add origin https://github.com/metomasso07Monica/animal-tales-by-jackson.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, go to **Settings**
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select: **main** branch
4. Select **"/ (root)"** folder
5. Click **Save**
6. Wait 2-5 minutes for deployment

### Step 4: Get Your Website URL

Your website will be live at:
```
https://metomasso07monica.github.io/animal-tales-by-jackson/
```

## 🎵 Adding Audio Files

1. Generate your 7 audio files in ElevenLabs (using Jackson's cloned voice)
2. Name them exactly:
   - `stretch.mp3`
   - `gary.mp3`
   - `penny.mp3`
   - `bruno.mp3`
   - `al.mp3`
   - `finn.mp3`
   - `benny.mp3`

3. Upload to the `audio/` folder in your GitHub repository
4. The audio players will automatically work!

## 📱 Creating QR Codes

Once your website is live, create QR codes for each story:

1. Go to https://www.qrcode-monkey.com/
2. For each animal, create a QR code with these URLs:
   - Stretch: `https://metomasso07monica.github.io/animal-tales-by-jackson/stretch.html`
   - Gary: `https://metomasso07monica.github.io/animal-tales-by-jackson/gary.html`
   - Penny: `https://metomasso07monica.github.io/animal-tales-by-jackson/penny.html`
   - Bruno: `https://metomasso07monica.github.io/animal-tales-by-jackson/bruno.html`
   - Al: `https://metomasso07monica.github.io/animal-tales-by-jackson/al.html`
   - Finn: `https://metomasso07monica.github.io/animal-tales-by-jackson/finn.html`
   - Benny: `https://metomasso07monica.github.io/animal-tales-by-jackson/benny.html`

3. Customize colors (optional - can use Christmas red/green)
4. Download each QR code
5. Add to your postcard back design in Canva

## 🦉 Adding Oliver the Owl Later

When Oliver's artwork is ready:

1. Upload the owl image as `8.png` to the `images/` folder
2. Create `oliver.html` (copy any story page and update the content)
3. Generate audio: `oliver.mp3` and upload to `audio/` folder
4. Update `index.html` - replace the "Coming Soon" card with the real Oliver link
5. Commit and push changes

## 🎨 Your Postcard Back Design

**Text for back of postcard:**
```
Scan to meet [Animal Name] and hear the story!

Story and art by Jackson, age 8
```

**Layout:**
- [QR Code - 1.5" square, centered]
- [Text above or beside QR code]
- [Optional: small teaser line like "Did you know giraffes can run 35 mph?"]

## 💡 Tips

- Test all QR codes before printing!
- Keep QR codes at least 1.5" x 1.5" for easy scanning
- Print test batch of 10-20 postcards first
- The website works on all phones and tablets
- Audio will play directly in browser - no app needed

## 🎉 You're Done!

Your complete storybook postcard system is ready to go!

Questions? Issues? Just update the files in GitHub and they'll automatically update on your website within a few minutes.

Good luck at the Christmas market on December 5th! 🎄
