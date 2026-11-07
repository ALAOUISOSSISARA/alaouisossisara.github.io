# Portfolio – Sara Alaoui Sossi

Static site: index.html + Sara_Alaoui_Sossi_CV.pdf. No build step.

## Put it online with Vercel
1. Create a GitHub repository (it can be private) and upload these files.
2. On vercel.com: Add New > Project > import the repository > Deploy (no settings to change).
3. In Project > Settings > Domains you can rename the link, e.g. sara-alaoui-sossi.vercel.app.

Without GitHub: install the Vercel CLI (`npm i -g vercel`), open this folder in a terminal and run `vercel --prod`.

## Update it
- Projects and internships: edit the <article class="entry"> blocks in index.html.
- Coverage table: each article's data-layers attribute decides its filled squares;
  the row names are in the `work` list at the bottom of the file.
- New CV: replace Sara_Alaoui_Sossi_CV.pdf, keeping the same file name.
