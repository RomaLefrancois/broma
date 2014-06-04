## [Broma](http://romalefrancois.github.io/broma)

An elegant, open source, fully responsive theme for [Jekyll](http://jekyllrb.com/). It includes lightweight styles and placeholder content to get you up and running with a simple blog in no time.

## Usage

### 1. Install Jekyll

Broma is built for use with Jekyll, so naturally you'll need to install that. On Macs, it's rather straightforward:

```bash
$ gem install jekyll
```

**Windows users:** Windows users have a bit more work to do, but luckily [@juthilo](https://github.com/juthilo) has your back with his [Run Jekyll on Windows](https://github.com/juthilo/run-jekyll-on-windows) guide.

You may also need to install Pygments, the Python syntax highlighter for code snippets that plays nicely with Jekyll. Read more about this [in the Jekyll docs](http://jekyllrb.com/docs/templates/#code_snippet_highlighting).

### 2a. Quick start

To help anyone with any level of familiarity with Jekyll quickly get started, Broma includes everything you need for a basic Jekyll site. To that end, just download Broma and start up Jekyll.

### 2b. Configure your own version of Broma

Open [_config.yml](_config.yml) and start editing the website configuration with your own informations.
<pre>
  firstname: John  
  lastname: Doe  
  title_prefix: "- John's website" # Will appears in the browser bar  
  description: "Your web site description"  
  ga_tag: "UA-XXXXXXXX-X"  # Your GA Tag
  twitter: "RomaLefrancois" # Your Twitter username
  github: "RomaLefrancois" # Your GitHub username
  linkedin: "https://www.linkedin.com/pub/johndoe"  # Your LinkedIn profile URL
</pre>
### 3. Running locally

To see your Jekyll site with Broma applied, start a Jekyll server. In Terminal, from `/broma` (or whatever your Jekyll site's root directory is named):

```bash
$ jekyll serve -- watch
```

Open <http://localhost:4000> in your browser, and voilà. You're done.

## Author

**Romain Lefrancois**  
<https://github.com/RomaLefrancois>  
<https://twitter.com/RomaLefrancois>


## License

Open sourced under the [MIT license](LICENSE.md).

Made with love in San Francisco. <3
