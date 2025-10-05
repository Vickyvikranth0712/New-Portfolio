# 📝 How to Edit Your Certificate Information

Your certificate images are now displaying! Now you need to update the text information for each certificate.

---

## 📍 Where to Edit

Open `index.html` and search for "Certificate Title 1" to find the certificates section.

---

## ✏️ Certificate 1

**Find this code:**
```html
<h3 class="cert-title">Certificate Title 1</h3>
<p class="cert-issuer"><i class="fas fa-award"></i> Issuing Organization</p>
<p class="cert-date"><i class="fas fa-calendar"></i> Issue Date</p>
<a href="#" class="cert-link">View Credential <i class="fas fa-external-link-alt"></i></a>
```

**Replace with your actual information:**
```html
<h3 class="cert-title">Your Certificate Name Here</h3>
<p class="cert-issuer"><i class="fas fa-award"></i> Google / Coursera / Udemy / etc</p>
<p class="cert-date"><i class="fas fa-calendar"></i> January 2024</p>
<a href="https://verify.yourlink.com/ABC123" target="_blank" class="cert-link">View Credential <i class="fas fa-external-link-alt"></i></a>
```

**Example:**
```html
<h3 class="cert-title">Python Programming Certification</h3>
<p class="cert-issuer"><i class="fas fa-award"></i> Google</p>
<p class="cert-date"><i class="fas fa-calendar"></i> March 2024</p>
<a href="https://www.coursera.org/verify/ABC123XYZ" target="_blank" class="cert-link">View Credential <i class="fas fa-external-link-alt"></i></a>
```

---

## ✏️ Certificate 2

**Find:** `Certificate Title 2`

**Update the same 4 fields:**
1. Certificate name
2. Issuing organization
3. Issue date
4. Verification link (or keep "#" if no link)

---

## ✏️ Certificate 3

**Find:** `Certificate Title 3`

**Update the same 4 fields**

---

## ✏️ Certificate 4

**Find:** `Certificate Title 4`

**Update the same 4 fields**

---

## 🎯 Quick Reference - What to Replace

For EACH certificate, replace:

| Field | Replace This | With Your Info | Example |
|-------|-------------|----------------|---------|
| Title | `Certificate Title 1` | Actual certificate name | `IoT Fundamentals` |
| Issuer | `Issuing Organization` | Company/Platform name | `Microsoft` |
| Date | `Issue Date` | Month and Year | `June 2023` |
| Link | `#` | Verification URL | `https://verify.com/ABC` |

---

## ⚠️ Important Notes

1. **Keep the HTML tags** - Don't delete `<h3>`, `<p>`, `<a>` tags
2. **Keep the icons** - Don't delete `<i class="fas fa-award"></i>` parts
3. **Add target="_blank"** to links - Makes them open in new tab
4. **No verification link?** - Just keep `href="#"` if the certificate has no online verification

---

## ✅ After Editing

1. Save the `index.html` file
2. Refresh your browser (Ctrl + F5 or Cmd + Shift + R)
3. Scroll to Certificates section
4. Check:
   - All certificate images show correctly
   - All titles are accurate
   - All organizations are correct
   - All dates are right
   - Links work (if added)
   - Carousel navigation works

---

## 🚀 You're Almost Done!

After updating all certificate information, your portfolio will be complete! 

The certificates will display in a beautiful carousel with:
- ✨ Your actual certificate images
- 📝 Proper titles and details
- 🔗 Working verification links
- 🎨 Smooth animations and hover effects
