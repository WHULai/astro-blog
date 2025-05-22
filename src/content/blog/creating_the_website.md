---
title: 'First post: Creating the Website'
description: ''
pubDate: 'May 20 2025'
heroImage: '/blog-placeholder-3.jpg'
---

Hi, everyone!

I'm Lai Wei, a college student from Wuhan University.

I created this website with `astro` using default blog template and Aliyun ECS.

To preview the website:

```bash
npm run dev
```

at the root directory.

To build the website:

```bash
npm run build
```

at the root directory.

To upload the compiled fold `dist`:

1. Ssh to the server and delete the original folder:

   ```bash
   cd /usr/share/nginx
   rm -r html
   ```

2. Sftp to the server and upload the `dist` folder:

   ```bash
   put -r /Users/weilai/Documents/Blogs/callous-comet/dist /usr/share/nginx/html
   ```
