# 📹🖼️ Media Upload Guide for Your Portfolio

## Step-by-Step Instructions

### **Step 1: Create Media Folders**
1. In your `Git Port` folder, create TWO new folders:
   - `videos` (for software project videos)
   - `images` (for hardware project images)

2. Your folder structure should look like this:

```
Git Port/
├── index.html
├── styles.css
├── script.js
├── VIDEO_UPLOAD_GUIDE.md (this file)
├── videos/              ← CREATE THIS FOLDER FOR SOFTWARE VIDEOS
│   ├── software-project1.mp4
│   └── software-project2.mp4
└── images/              ← CREATE THIS FOLDER FOR HARDWARE IMAGES
    ├── hardware-project1.jpg
    ├── hardware-project2.jpg
    └── hardware-project3.jpg
```

---

## 📹 **SOFTWARE PROJECTS (Videos)**

### **Step 2: Prepare Your Videos**

#### **Video Requirements:**
- **Format**: MP4 (recommended), WebM, or OGG
- **Size**: Try to keep under 50MB per video for faster loading
- **Resolution**: 1280x720 (HD) or 1920x1080 (Full HD)
- **Duration**: Keep videos concise (30 seconds - 2 minutes recommended)

#### **How to Compress Videos (if too large):**

**Option 1: Using Online Tools**
- Visit: https://www.freeconvert.com/video-compressor
- Upload your video
- Compress and download

**Option 2: Using VLC Media Player (Free)**
1. Open VLC → Media → Convert/Save
2. Add your video file
3. Choose profile: "Video - H.264 + MP3 (MP4)"
4. Set destination and convert

### **Step 3: Rename Your Software Videos**

Rename your video files to these EXACT names:

**Software Projects (2 videos):**
- `software-project1.mp4`
- `software-project2.mp4`

### **Step 4: Copy Videos to the Folder**

1. Copy/move both renamed videos into the `videos` folder
2. Double-check the names match exactly (case-sensitive!)

---

## 🖼️ **HARDWARE PROJECTS (Images)**

### **Step 5: Prepare Your Images**

#### **Image Requirements:**
- **Format**: JPG, JPEG, PNG, or WebP
- **Size**: Recommended under 2MB per image
- **Resolution**: 1280x720 or higher (landscape orientation preferred)
- **Quality**: High quality, clear images of your hardware projects

#### **How to Resize/Compress Images:**

**Option 1: Using Online Tools**
- Visit: https://tinypng.com or https://compressor.io
- Upload your image
- Download compressed version

**Option 2: Using Paint/Photos (Windows)**
1. Open image in Paint or Photos
2. Resize to 1280x720 pixels
3. Save as JPEG with high quality

### **Step 6: Rename Your Hardware Images**

Rename your image files to these EXACT names:

**Hardware Projects (3 images):**
- `hardware-project1.jpg`
- `hardware-project2.jpg`
- `hardware-project3.jpg`

### **Step 7: Copy Images to the Folder**

1. Copy/move all 3 renamed images into the `images` folder
2. Double-check the names match exactly (case-sensitive!)

---

## ✅ **Step 8: Verify It Works**

1. Open `index.html` in your browser
2. Navigate to the Projects section
3. Click on "Software Projects" tab → Videos should load and be playable
4. Click on "Hardware Projects" tab → Images should display with hover effects
5. Images should zoom slightly when you hover over them

---

## 🎨 **Customization Options**

### **Want to Use Different File Names?**

#### For Videos:
Edit the `index.html` file and find:
```html
<source src="videos/software-project1.mp4" type="video/mp4">
```

Change to your file name:
```html
<source src="videos/MY_VIDEO_NAME.mp4" type="video/mp4">
```

#### For Images:
Edit the `index.html` file and find:
```html
<img src="images/hardware-project1.jpg" alt="Hardware Project 1">
```

Change to your file name:
```html
<img src="images/MY_IMAGE_NAME.jpg" alt="My Project">
```

### **Want Different Image Formats?**

You can use PNG or WebP instead of JPG:
- Just use `.png` or `.webp` extension
- Update the file name in HTML accordingly

---

## 🐛 **Troubleshooting**

### **Video Not Showing?**
- ✅ Check file name spelling (case-sensitive!)
- ✅ Make sure video is in MP4 format
- ✅ Verify the `videos` folder is in the same directory as `index.html`
- ✅ Check browser console (F12) for errors

### **Image Not Showing?**
- ✅ Check file name spelling and extension (.jpg, .png, etc.)
- ✅ Make sure image is in the `images` folder
- ✅ Try opening the image directly: right-click → "Open image in new tab"
- ✅ Check file permissions (should be readable)

### **Video Not Playing?**
- ✅ Try a different browser (Chrome, Firefox, Edge)
- ✅ Convert video to MP4 format
- ✅ Reduce video file size

### **Image Looks Stretched/Distorted?**
- The CSS is set to `object-fit: cover` which crops to fit
- Use landscape images (wider than tall) for best results
- Or change to `object-fit: contain` in `styles.css`:

```css
.project-image img {
    object-fit: contain; /* Change from 'cover' to 'contain' */
}
```

---

## 📝 **Quick Checklist**

### Software Projects:
- [ ] Created `videos` folder
- [ ] Prepared 2 videos in MP4 format
- [ ] Renamed videos correctly:
  - [ ] software-project1.mp4
  - [ ] software-project2.mp4
- [ ] Copied videos to `videos` folder
- [ ] Tested in browser - videos play

### Hardware Projects:
- [ ] Created `images` folder
- [ ] Prepared 3 images (JPG/PNG)
- [ ] Renamed images correctly:
  - [ ] hardware-project1.jpg
  - [ ] hardware-project2.jpg
  - [ ] hardware-project3.jpg
- [ ] Copied images to `images` folder
- [ ] Tested in browser - images display with hover effect

---

## 🎯 **Current Media Paths in Your Code:**

**Software Projects (Videos):**
1. `videos/software-project1.mp4` (left side with "View Code" button)
2. `videos/software-project2.mp4` (right side with "View Code" button)

**Hardware Projects (Images):**
1. `images/hardware-project1.jpg` (left side, no buttons)
2. `images/hardware-project2.jpg` (right side, no buttons)
3. `images/hardware-project3.jpg` (left side, no buttons)

---

## 💡 **Pro Tips:**

### For Videos:
1. **Optimize for Web**: Use tools like HandBrake
2. **Keep it Short**: 30-60 second demos work best
3. **Add Captions**: Consider adding text overlays in your videos

### For Images:
1. **Good Lighting**: Use well-lit, clear photos
2. **Multiple Angles**: Consider showing different views of your hardware
3. **Clean Background**: Remove clutter from photos
4. **High Resolution**: Use at least 1280x720 pixels
5. **Landscape Orientation**: Wider images work better than tall ones

### General:
1. **Compress Files**: Smaller files = faster loading
2. **Test on Mobile**: Check how media looks on phones/tablets
3. **Backup**: Keep original high-quality files in a separate folder

---

**Need Help?** If media still doesn't work, check:
- File permissions (folders should be readable)
- File formats are web-compatible
- No spaces or special characters in file names
- Correct folder structure

Good luck with your portfolio! 🚀
