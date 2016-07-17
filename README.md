# portfolio-fend

#Portfolio
Portfolio is a site built to display Danielle R. Simon's web and software projects. The site was built using HTML5, CSS3 and Bootstrap as a project for  [Udacity.com's](http://www.udacity.com "Udacity") [Front-end nanodegree course](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001 "Udacity Front-End Nanodegree"). View the [slightly, insignificantly modified version of the] portfolio [here](https://drsimonxx.github.io/portfolio-fend/ "Danielle R. Simon's Portfolio").

##How To Use the Portfolio
- Click the images to view a modal popup that presents the project information.
- Follow the link provided underneath each project in order to view the project or to be taken to a site where you can download the project.

##Code Modification
The code between the master branch and the gh-pages branch had to be changed just slightly in order to display the portfolio correctly on GitHub. The main issue was with the entypo icon font used in the top left-hand corner of the portfolio site, which created a mixed connection error (http vs https) preventing its display, as switching the icon font link to //weloveiconfonts.com/api/?family=entypo or https://weloveiconfonts.com/api/?family=entypo does not work in this instance. On the gh-pages branch, the icon font is substituted for a slightly different .svg image as a workaround. View the CSS and index.html files to view the differences between the code on the master branch and the gh-pages branch. 



