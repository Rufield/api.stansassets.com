# Stan's Assets API website
This project is used to maintent the docfx project for the [Web Stan's Assets API](https://api.stansassets.com/)

### How to use
* Webiste is located under the `docs` folder.
* Make sure docfx is installed. (for example if you are using  mac [Homebrew](https://formulae.brew.sh/formula/docfx) run `brew install docfx`). Or cehcek **DocFX** section for more details.
* To regenerate the website content, remove files under the `docs` folder, run `docfx docfx-project/docfx.json` 
* If you want to preview created site locally, run `docfx docfx-project/docfx.json -t statictoc`
* Make sure you have the following repos on the smae level
* * Plugins
* * com.stansassets.foundation

### DocFx
* [Getting Starged Guide](https://dotnet.github.io/docfx/tutorial/docfx_getting_started.html)
* [Themes](https://dotnet.github.io/docfx/templates-and-plugins/templates-dashboard.html)

Other nice looking static websites powered by DocFx
* Testify [Git repo](https://github.com/wekempf/testify) | [Website](http://wekempf.github.io/testify/)

### Github pages
Static site will be hoster from the `master` branch /  `master` branch docs folder / `gh-pages` branch (what ever you preffer in the settins.)

*Subdomain set up:*
* Repo Options - set custom subdomain to `api.stansassets.com`
* Add doman `CNAME` record: `api / stansassets.github.io`


*Tutorials / Info*
* [How to Use a GoDaddy Custom Subdomain with GitHub Pages Hosting](https://medium.com/@SeloSlav/how-to-use-a-godaddy-custom-subdomain-with-github-pages-hosting-fbac17f36f9d)
* [Using custom domain for GitHub pages](https://medium.com/@hossainkhan/using-custom-domain-for-github-pages-86b303d3918a)
* [Does GitHub Pages Support HTTPS for www and @ subdomains?](https://github.community/t5/GitHub-Pages/Does-GitHub-Pages-Support-HTTPS-for-www-and-subdomains/td-p/7116)
