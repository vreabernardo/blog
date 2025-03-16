# My Jekyll Blog

A minimal Jekyll blog to publish posts.

## How to Add a New Post

1. Create a new file in the `_posts` directory with the naming format: `YYYY-MM-DD-title.md`
   - For example: `2024-09-10-my-new-post.md`

2. Add the following front matter at the top of the file:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD HH:MM:SS -0700
   categories: blog
   ---
   ```

3. Write your post content in Markdown below the front matter.

You can copy `_posts/TEMPLATE.md` as a starting point for new posts.

## Running Locally

Run the following command to preview the blog locally:

```
bundle exec jekyll serve
```

Then open your browser to [http://localhost:4000](http://localhost:4000)

## Publishing Changes

After creating or updating posts, commit and push your changes:

```
git add .
git commit -m "Add new post: Title"
git push
``` 