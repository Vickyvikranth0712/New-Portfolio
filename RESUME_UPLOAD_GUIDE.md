# 📄 Resume Upload Guide

Follow these simple steps to add your resume to the portfolio.

---

## 📁 STEP 1: Prepare Your Resume File

### File Requirements:
- **Format**: PDF (Recommended) - Most professional and universal
- **File Size**: Under 2MB for fast downloads
- **Quality**: Make sure text is readable and layout is proper

### File Naming:
**Rename your resume file to exactly:** `resume.pdf`

⚠️ **Important**: 
- Use lowercase letters: `resume.pdf` (NOT `Resume.pdf` or `RESUME.pdf`)
- No spaces in the filename
- Must be `.pdf` extension

---

## 📂 STEP 2: Upload Resume to Your Portfolio

1. **Open File Explorer**
2. **Navigate to:** `C:\Users\aishw\OneDrive\Desktop\Git Port`
3. **Copy your `resume.pdf` file**
4. **Paste it directly in the `Git Port` folder** (same location as `index.html`)

### Your folder structure should look like:
```
Git Port/
├── assets/
│   ├── images/
│   └── videos/
├── index.html
├── script.js
├── styles.css
├── resume.pdf          ← Your resume goes here!
└── README.md
```

---

## ✅ STEP 3: Test the Resume Download

1. **Open your portfolio** in a browser (open `index.html`)
2. **Look at the top-right corner** - You'll see the navbar with two buttons
3. **Click the Download icon** (orange circular button on the left)
4. **Your resume should download** as `Vikranth_V_Resume.pdf`

---

## 🎯 How It Works

When users click the download button:
- The button triggers a download of `resume.pdf`
- File is automatically renamed to `Vikranth_V_Resume.pdf` for the user
- Download happens instantly without leaving the page
- Works on all devices (desktop, mobile, tablet)

---

## ⚠️ Troubleshooting

### Problem: "Resume file not found" alert appears
**Solution:**
- Check that file is named exactly `resume.pdf` (lowercase)
- Verify file is in the main `Git Port` folder (not in assets or images)
- Make sure file extension is `.pdf` (not `.docx` or other formats)

### Problem: File won't download
**Solution:**
- Check browser permissions (allow downloads)
- Try a different browser (Chrome, Firefox, Edge)
- Clear browser cache (Ctrl + F5)

### Problem: Wrong file downloads
**Solution:**
- Delete old `resume.pdf` from the folder
- Add your new `resume.pdf`
- Refresh the browser

---

## 📝 Updating Your Resume Later

When you want to update your resume:
1. Delete the old `resume.pdf` from the `Git Port` folder
2. Add your new updated `resume.pdf` (same name)
3. That's it! No code changes needed
4. The download button will automatically serve the new file

---

## 🎨 Optional: Customize Download Filename

If you want to change the downloaded filename (default is `Vikranth_V_Resume.pdf`):

1. Open `script.js`
2. Find line with: `link.download = 'Vikranth_V_Resume.pdf';`
3. Change `Vikranth_V_Resume.pdf` to whatever you want
4. Example: `link.download = 'John_Doe_Resume.pdf';`

---

## ✅ Quick Checklist

- [ ] Resume file converted to PDF format
- [ ] File renamed to exactly `resume.pdf` (lowercase)
- [ ] File placed in main `Git Port` folder (same level as index.html)
- [ ] Opened portfolio in browser
- [ ] Clicked download button to test
- [ ] Resume downloaded successfully as `Vikranth_V_Resume.pdf`

---

## 🚀 You're Done!

Once the `resume.pdf` is in place, your portfolio is fully functional!

Users can now:
- ✅ View your projects with videos/images
- ✅ See your certificates in the carousel
- ✅ Download your resume with one click
- ✅ Connect with you via social media

**Just place `resume.pdf` in the Git Port folder and reply "Done" when ready!**
