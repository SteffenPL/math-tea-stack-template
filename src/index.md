---
title: "About me"
date: 2022-05-28T21:55:16+02:00
layout: markdown
---


<div class="sm:float-right sm:max-w-[12em] sm:ml-2 md:flex hidden drop-shadow-xl">
<img src="https://upload.wikimedia.org/wikipedia/en/4/46/Toph_Beifong.png">
</div>

I am **Toph**! The best earth-bender the world has ever seen.

<div class="container md:hidden drop-shadow-xl">
<img class="mx-auto max-w-[12em]" src="https://upload.wikimedia.org/wikipedia/en/4/46/Toph_Beifong.png">
</div>


## Contact

<small>
E-Mail: <a href="mailto:toph@earth.bending">toph@earth.bending</a>
</small>

## Publications

1. **Toph, [Katara](https://avatar.fandom.com/de/wiki/Katara),** _On the challenges of balance in the world_ [arxiv](https://arxiv.org/), [submitted].




<hr>

## Examples 
 

### Single page templates

To add a single page, you just need to do two steps:
1. Create a new markdown file `.md` and add the header
```md
---
title: Perfect single page
layout: markdown
---

## {{ title }}

Add you content here

```
2. Add your content in that file using markdown and/or html.
3. You might want to add the page to the navigation menu. For this, add this to 
```js
 { name: 'Perfect page', route: '/perfect_page' },
```
4. If you want to add links to this page from elsewhere, either use relative links (the path needs to be relative to the current file)
```md
[Link to the perfect page](./perfect_page)
```
or to generate an absolute link, use
```md
[Link to the perfect page]({{ '/perfect_page' }})
```
The `| url` command adds the `pathPrefix`, which might be necessary for the uploaded webpage to add a university-specific prefix. 

