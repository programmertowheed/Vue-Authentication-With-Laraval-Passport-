<template>
  <div class="container py-4">
    <main class="bd-main order-1">
      <div class="bd-intro ps-lg-4">
        <div class="d-md-flex flex-md-row-reverse align-items-center justify-content-between">
          <a class="btn btn-sm btn-bd-light mb-2 mb-md-0" href="https://github.com/twbs/bootstrap/blob/main/site/content/docs/5.0/about/overview.md" title="View and edit this file on GitHub" target="_blank" rel="noopener">View on GitHub</a>
          <h1 class="bd-title" id="content">About</h1>
        </div>
        <p class="bd-lead">Learn more about the team maintaining Bootstrap, how and why the project started, and how to get involved.</p>
      </div>

      <div class="bd-content ps-lg-4">
        <h2 id="team">Team<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="#" href="#team" style="padding-left: 0.375em;"></a></h2>
        <p>Bootstrap is maintained by a <a href="https://github.com/orgs/twbs/people">small team of developers</a> on GitHub. We’re actively looking to grow this team and would love to hear from you if you’re excited about CSS at scale, writing and maintaining vanilla JavaScript plugins, and improving build tooling processes for frontend code.</p>
        <h2 id="history">History<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="#" href="#history" style="padding-left: 0.375em;"></a></h2>
        <p>Originally created by a designer and a developer at Twitter, Bootstrap has become one of the most popular front-end frameworks and open source projects in the world.</p>
        <p>Bootstrap was created at Twitter in mid-2010 by <a href="https://twitter.com/mdo">@mdo</a> and <a href="https://twitter.com/fat">@fat</a>. Prior to being an open-sourced framework, Bootstrap was known as <em>Twitter Blueprint</em>. A few months into development, Twitter held its <a href="https://blog.twitter.com/engineering/en_us/a/2010/hack-week.html">first Hack Week</a> and the project exploded as developers of all skill levels jumped in without any external guidance. It served as the style guide for internal tools development at the company for over a year before its public release, and continues to do so today.</p>
        <p>Originally <a href="https://blog.twitter.com/developer/en_us/a/2011/bootstrap-twitter.html">released</a> on <time datetime="2011-08-19 11:25">Friday, August 19, 2011</time>, we’ve since had over <a href="https://github.com/twbs/bootstrap/releases">twenty releases</a>, including two major rewrites with v2 and v3. With Bootstrap 2, we added responsive functionality to the entire framework as an optional stylesheet. Building on that with Bootstrap 3, we rewrote the library once more to make it responsive by default with a mobile first approach.</p>
        <p>With Bootstrap 4, we once again rewrote the project to account for two key architectural changes: a migration to Sass and the move to CSS’s flexbox. Our intention is to help in a small way to move the web development community forward by pushing for newer CSS properties, fewer dependencies, and new technologies across more modern browsers.</p>
        <p>Our latest release, Bootstrap 5, focuses on improving v4’s codebase with as few major breaking changes as possible. We improved existing features and components, removed support for older browsers, dropped jQuery for regular JavaScript, and embraced more future-friendly technologies like CSS custom properties as part of our tooling.</p>
        <h2 id="get-involved">Get involved<a class="anchorjs-link " aria-label="Anchor" data-anchorjs-icon="#" href="#get-involved" style="padding-left: 0.375em;"></a></h2>
        <p>Get involved with Bootstrap development by <a href="https://github.com/twbs/bootstrap/issues/new">opening an issue</a> or submitting a pull request. Read our <a href="https://github.com/twbs/bootstrap/blob/v5.0.2/.github/CONTRIBUTING.md">contributing guidelines</a> for information on how we develop.</p>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "About"
}
</script>

<style scoped>

</style>