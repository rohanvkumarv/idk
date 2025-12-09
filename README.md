# Stravise Blog Pages

This repository contains the blog pages for the Stravise website.

## Structure

```
/blog
  ├── index.html              # Blog listing page
  ├── blog-detail.html        # Blog detail template
  └── strategic-planning.html # Sample blog post
```

## Pages

### Blog Listing Page (`/blog/index.html`)
- Clean grid layout showing blog cards
- 3-column responsive grid
- Each card includes:
  - Featured image
  - Title
  - Category
  - Date
  - Optional percentage indicator
- No sidebar
- Full-width hero section with breadcrumb

### Blog Detail Pages (`/blog/*.html`)
- Individual blog post layout
- Includes:
  - Hero section with breadcrumb
  - Featured image
  - Meta information (date, read time, category)
  - Blog content with headings and paragraphs
  - Image grid support
  - Quote blocks with author attribution
  - Tags and social share buttons
  - Popular tags sidebar
  - Comments section (3 comments)
  - Comment reply form

## Technologies Used

- HTML5
- Bootstrap 5.3.2
- Font Awesome 6.4.2
- Google Fonts (Outfit)

## Usage

To create a new blog post:
1. Copy `blog-detail.html` or `strategic-planning.html`
2. Rename it with your desired slug (e.g., `my-blog-post.html`)
3. Update the content, images, and meta information
4. Add a link to it from `index.html`

## Notes

- No header/footer included as per requirements
- Images use placeholder URLs (Unsplash, Pravatar)
- Fully responsive design
- Clean, modern styling matching the Stravise brand
