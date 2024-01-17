Updated version of "mcdowellcv" from https://github.com/dnl-blkv/mcdowell-cv

Updated with:
  - Modified header:
    - Icons for location, phone, email, Github, LinkedIn
  - Added hyperlinks (for Github, LinkedIn, projects)
  - Modified color of horizontal line separators
  - Modified vertical spacing
  
To run:
  - Install LaTeX if not installed 
    - on Ubuntu: sudo apt install texlive-full (installs full installation of LaTeX, uses about 5 GB)
  - Edit 'CV_Template.tex' with info (warning: there's a good bit of "spaghetti code" from my updates...)
  - In the directory containing 'CV_Template.tex', 'mcdowellcv_updated.cls', and the 'images' directory:
    - run in terminal: 'lualatex CV_Template.tex'
    - A 'CV_Template.pdf' file should generate in the same directory if it successfully ran.
