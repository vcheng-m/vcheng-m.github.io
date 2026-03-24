# Your New Multi-Page Website - Instructions

## What You Have

I've created a clean, professional multi-page website inspired by Diana Moreira and Violeta Haas's sites:

1. **index.html** - Landing page with your bio and photo
2. **research.html** - Publications and working papers with journal cover images
3. **teaching.html** - Your teaching experience

## Upload to GitHub

1. Go to https://github.com/vcheng-m/vcheng-m.github.io
2. Upload all three HTML files:
   - index.html
   - research.html
   - teaching.html
3. Wait 2-3 minutes
4. Visit https://vcheng-m.github.io

## Adding Your Photo

1. Save your professional headshot as `photo.jpg`
2. Upload it to your GitHub repository
3. In `index.html`, find this line (around line 148):
   ```html
   <!-- Replace with your photo: <img src="photo.jpg" alt="Vanessa Cheng-Matsuno"> -->
   ```
4. Remove the `<!--` and `-->` to uncomment it
5. Delete or comment out the placeholder line below it

## Adding Journal Cover Images (Like Violeta Haas)

This is the cool part! Here's how to add journal cover images:

### Step 1: Create an images folder
1. In your GitHub repository, create a new folder called `images`

### Step 2: Get journal cover images
You can find journal covers by:
- Googling "[Journal Name] cover" (e.g., "Electoral Studies journal cover")
- Visiting the journal's website
- Taking screenshots of journal covers from your publications

Save them as:
- `ejpr-cover.jpg` (European Journal of Political Research)
- `res-politics-cover.jpg` (Research & Politics)
- `electoral-studies-cover.jpg` (Electoral Studies)

### Step 3: Upload images to GitHub
1. Go to your `images` folder in GitHub
2. Click "Add file" → "Upload files"
3. Upload all three journal cover images

### Step 4: Update research.html
In `research.html`, find these lines and uncomment them:

For the first publication (around line 120):
```html
<!-- Add journal cover image: <img src="images/ejpr-cover.jpg" alt="EJPR"> -->
```
Remove the `<!--` and `-->` and delete the placeholder div below it.

Do the same for the other two publications.

## Color Palette

The site uses the professional blue palette from Diana and Violeta's sites:
- **Primary blue:** #0066cc (links)
- **Hover blue:** #004499 (link hover)
- **Text:** #333 (dark gray)
- **Borders:** #ddd (light gray)

## Customizing

### Change colors:
Find and replace these in all three HTML files:
- `#0066cc` - Main link color
- `#004499` - Hover color

### Update content:
All your real information is already there! You can edit directly in GitHub or in a text editor.

## Tips

- Keep the Georgia/Times font - it's the academic standard used by both Diana and Violeta
- The layout is designed to be simple and content-focused
- Journal images should be roughly 120px wide for best results

## Questions?

Let me know if you need help with:
- Finding journal cover images
- Adjusting the layout
- Adding more sections
- Anything else!