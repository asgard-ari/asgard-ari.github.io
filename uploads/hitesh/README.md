Place photos from Hitesh's defense here so the site can serve them.

From your machine run:

```bash
# create the folder if it doesn't exist in the repo root
mkdir -p static/uploads/hitesh
# copy all images from your Desktop folder into the site
cp ~/Desktop/hitesh/* static/uploads/hitesh/
# optionally rename the main image to defense-1.jpg
# (adjust names if needed)
# then run the hugo dev server to preview
hugo server -D --disableFastRender --minify
```

The news post created at `content/post/2025-11-29-hitesh-kishore-das-defends-phd.md` references `/uploads/hitesh/defense-1.jpg` as the featured image and includes a small gallery (defense-2.jpg, defense-3.jpg).
