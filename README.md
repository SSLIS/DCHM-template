[![DOI](https://zenodo.org/badge/471756787.svg)](https://zenodo.org/badge/latestdoi/471756787)

# DCHM-template

This is a template that was specifically designed to help students of the Digitising Cultural Heritage Materials (DCHM) course at the University of Borås publish their digitisation projects online with GitHub Pages. 
But it can be used by anyone who wants to try GitHub Pages to publishing a simple HTML-based website.

🚀[Visit the Website](https://sslis.github.io/DCHM-template/) if you want to see what the published version of this repository looks like.

An example of what the template can turn into can be found in Wout's [DIY-frankensTEIn](https://sslis.github.io/DIY-frankensTEIn/index.html) repository.
For more information on the template and how to get started yourself, please refer to [the repository's wiki](https://github.com/SSLIS/DCHM-template/wiki).  

## A Note on Using the Template
This template contains a series of files that are important for archiving purposes, and for upholding community standards, such as our [license information](LICENSE), and [Zenodo JSON metadata](.zenodo.json). While these files are useful to contextualize this specific repository, they would be irrelevant (or even contain false information) when copied over into the user's own repository. (For example: the [license](LICENSE) would identify me as the copyright holder of your repository.)

To resolve this issue, the template uses GitHub Actions to delete some irrelevant files (and modify others). This happens **after** the user creates their own copy of the repository, and results in a subsequent bot-made `commit`, that cleans up the template. Where, initially, your repository will look exactly like this one (including the [license](LICENSE) etc.), these superfluous files will disapear when the process is finished. 

This process takes some time, albeit usually less than a minute. You may need to refresh your page to see it take effect. You will notice that the process was succesful when a number of files have been removed from your repository, and this README.md file instead contains some dummy text.

I would recommend that you wait until this process is finished (which should not take long) before cloning your repository to your local machine, and starting to modify it. If you do not notice any changes after some time, remember to refresh your page. You can also always go and check if the process is still running (and if anything has gone wrong) by navigating to the `Actions` tab at the top of your repository's page.

## Credits
This repository was originally developed by [Wout Dillen](https://github.com/WoutDLN) as a teaching tool in the Digitising Cultural Heritage Materials course at the [University of Borås](https://www.hb.se/), where he currently works as a Senior Lecturer in Library and Information Science. Continued development of the template has in part been made possible by [Huminfra](https://www.huminfra.se), the Swedish national infrastructure project for Digital Humanities.

Special thanks to [vincerubinetti](https://github.com/vincerubinetti), whose GitHub Action (mentioned in [this forum comment](https://github.com/orgs/community/discussions/22183#discussioncomment-4585507)) formed the basis of the template cleanup procedure mentioned above, and to [Andre601](https://github.com/Andre601), for helping me figure out how to update the `.yml` file to get it to work.
