
<h1 align="center">
Zhengkun Li's Academic Homepage
</h1>

<div align="center">

[![](https://img.shields.io/github/stars/Zhengkun-Li/Zhengkun-Li.github.io)](https://github.com/Zhengkun-Li/Zhengkun-Li.github.io)
[![](https://img.shields.io/github/license/Zhengkun-Li/Zhengkun-Li.github.io)](https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/LICENSE)

</div>

<p align="center">A Modern and Responsive Academic Personal Homepage</p>

<p align="center">
    <br>
    <a href="https://zhengkun-li.github.io/">Visit My Homepage</a>
    <br>
</p>

## Key Features
- **Automatically update google scholar citations**: using the google scholar crawler and github action, this REPO can update the author citations and publication citations automatically.
- **Support Google analytics**: you can trace the traffics of your homepage by easy configuration.
- **Responsive**: this homepage automatically adjust for different screen sizes and viewports.
- **Beautiful and Simple Design**: this homepage is beautiful and simple, which is very suitable for academic personal homepage.
- **SEO**: search Engine Optimization (SEO) helps search engines find the information you publish on your homepage easily, then rank it against similar websites.
- **Project Detail Pages**: create dedicated pages for each project with organized structure, image galleries, and documentation.
- **Image Gallery**: automatic image gallery with lightbox support for project images.

## About This Website

This is my personal academic homepage built with Jekyll, featuring:

- Modern, responsive design optimized for academic content
- Automatic Google Scholar citation updates
- Project detail pages with image galleries
- Clean and professional presentation of research work

## Quick Start (For Developers)
1. Configure the google scholar citation crawler:
    1. Find your google scholar ID in the url of your google scholar page (e.g., https://scholar.google.com/citations?user=SCHOLAR_ID), where `SCHOLAR_ID` is your google scholar ID.
    1. Set GOOGLE_SCHOLAR_ID variable to your google scholar ID in `Settings -> Secrets -> Actions -> New repository secret` of the REPO website with `name=GOOGLE_SCHOLAR_ID` and `value=SCHOLAR_ID`.
    1. Click the `Action` of the REPO website and enable the workflows by clicking *"I understand my workflows, go ahead and enable them"*. This github action will generate google scholar citation stats data `gs_data.json` in `google-scholar-stats` branch of your REPO. When you update your main branch, this action will be triggered. This action will also be trigger 08:00 UTC everyday.
1. Generate favicon using [favicon-generator](https://redketchup.io/favicon-generator) and download all generated files to `REPO/images`.
1. Modify the configuration of your homepage `_config.yml`:
    1. `title`: the title of your homepage
    1. `description`: the description of your homepage
    1. `repository`: USER_NAME/REPO_NAME  
    1. `google_analytics_id` (optional): google analytics ID
    1. SEO Related keys (optional): get these keys from search engine consoles (e.g. Google, Bing and Baidu) and paste here.
    1. `author`: the author information of this homepage, including some other websites, emails, city and univeristy.
    1. More configuration details are described in the comments.
1. Add your homepage content in `_pages/about.md`.
    1. You can use html+markdown syntax just same as jekyll.
    1. You can use a `<span>` tag with class `show_paper_citations` and attribute `data` to display the citations of your paper. Set the data to the google scholar paper ID. For
        ```html
        <span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span>
        ``` 
        > Q: How to get the google scholar paper ID?   
        > A: Enter your google scholar homepage and click the paper name. Then you can see the paper ID from `citation_for_view=XXXX`, where `XXXX` is the required paper ID.
1. (Optional) Create project detail pages:
    1. Create a folder for each project in `project/` directory with the following structure:
       ```
       project/
       └── project_name/
           ├── index.md           # Project detail page (markdown)
           ├── documents/         # PDF files, posters, papers
           └── images/            # Project images for gallery
       ```
    1. Create `index.md` with front matter and project description (see `project/blueberry_yield_estimation/index.md` for example)
    1. Add images to `images/` folder - they will automatically appear in the gallery
    1. Link project images in `about.md` to point to `/project/project_name/`
1. Your page will be published at `https://USERNAME.github.io`.

## Project Structure

The project uses an organized folder structure for managing project resources:

```
project/
├── project_name/
│   ├── index.md           # Project detail page (Markdown format)
│   ├── documents/         # PDF files, posters, conference papers
│   └── images/            # Project images (auto-displayed in gallery)
```

### Creating a Project Detail Page

1. Create a new folder in `project/` directory: `project/your_project_name/`
2. Create subdirectories: `documents/` and `images/`
3. Create `index.md` with the following structure:
   ```markdown
   ---
   layout: default
   title: "Your Project Title"
   permalink: /project/your_project_name/
   author_profile: true
   ---
   
   # Your Project Title
   
   Project description here...
   
   ## 📸 Project Gallery
   
   {% include gallery.html 
      folder="project/your_project_name/images" 
      title="Project Images" 
      columns="3" 
   %}
   ```
4. Add images to `images/` folder - they will automatically appear in the gallery
5. Add PDFs and documents to `documents/` folder
6. Link to the project page in `_pages/about.md`:
   ```html
   <a href="/project/your_project_name/">
     <img src="path/to/image.jpg" alt="Project">
   </a>
   ```

## Debug Locally

1. Clone your REPO to local using `git clone`.
1. Install Jekyll building environment, including `Ruby`, `RubyGems`, `GCC` and `Make` following [the installation guide](https://jekyllrb.com/docs/installation/#requirements).
1. Run `bash run_server.sh` to start Jekyll livereload server.
1. Open http://127.0.0.1:4000 in your browser.
1. If you change the source code of the website, the livereload server will automatically refresh.
1. When you finish the modification of your homepage, `commit` your changes and `push` to your remote REPO using `git` command.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Credits

This website uses the following open-source libraries and frameworks:
- [Font Awesome](https://fontawesome.com/) - Icons (SIL OFL 1.1 and MIT License)
- [Jekyll](https://jekyllrb.com/) - Static site generator
- [Lightbox2](https://lokeshdhakar.com/projects/lightbox2/) - Image gallery
