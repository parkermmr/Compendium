<style>
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    position: relative;
}
.watermark {
    position: fixed;
    top: 35%;
    left: 10%;
    width: 80%;
    text-align: center;
    font-size: 80px;
    font-weight: bold;
    color: rgba(255, 0, 0, 0.1); 
    transform: rotate(-30deg);
    z-index: -1;
    pointer-events: none;
}
.headerTitle {
  font-size: 45px;
  text-align: center;
}
.tab {
  display: inline-block;
  margin-left: 40px;
}
#backdrop {
  padding: 100 0 100 0;
  display: flex;
  justify-content: center;
  align-items: center;
}
.visually-hidden {
    clip: rect(0 0 0 0);
    clip-path: inset(100%);
    height: 1px;
    overflow: hidden;
    position: absolute;
    width: 1px;
    white-space: nowrap;
}
.toc-list, .toc-list ol {
  list-style-type: none;
}
.toc-list {
  padding: 0;
}
.toc-list ol {
  padding-inline-start: 2ch;
}
.toc-list > li > a {
  font-weight: bold;
  margin-block-start: 1em;
}
.toc-list li > a {
    text-decoration: none;
    display: grid;
    grid-template-columns: auto max-content;
    align-items: end;
}
.toc-list li > a > .title {
    position: relative;
    overflow: hidden;
}
.toc-list li > a .leaders::after {
    position: absolute;
    padding-inline-start: .25ch;
    content: " . . . . . . . . . . . . . . . . . . . "
        ". . . . . . . . . . . . . . . . . . . . . . . "
        ". . . . . . . . . . . . . . . . . . . . . . . "
        ". . . . . . . . . . . . . . . . . . . . . . . "
        ". . . . . . . . . . . . . . . . . . . . . . . "
        ". . . . . . . . . . . . . . . . . . . . . . . "
        ". . . . . . . . . . . . . . . . . . . . . . . ";
    text-align: right;
}
.toc-list li > a > .page {
    min-width: 2ch;
    font-variant-numeric: tabular-nums;
    text-align: right;
}
</style>

<div class="watermark">DRAFT</div>

<h1 id="headerTitle">Compendium CI/CD Suite</h1>

<h2>Table of Contents</h2>
<ol class="toc-list" role="list">
  <li>
    <a href="#overview">
      <span class="title">Overview<span class="leaders" aria-hidden="true"></span></span>
    </a>
    <ol role="list">
      <li>
        <a href="#compendium">
          <span class="title">What is Compendium?<span class="leaders" aria-hidden="true"></span></span>
        </a>
      </li>
      <li>
        <a href="#capabilities">
          <span class="title">What are Compendium's capabilities?<span class="leaders" aria-hidden="true"></span></span>
        </a>
      </li>
      <li>
        <a href="#who">
          <span class="title">Who is Compendium for?<span class="leaders" aria-hidden="true"></span></span>
        </a>
      </li>
    </ol>
  </li>
  <li>
    <a href="#technical">
      <span class="title">Technical Details<span class="leaders" aria-hidden="true"></span></span>
    </a>
    <ol role="list">
      <li>
        <a href="#architecture">
          <span class="title">Architecture<span class="leaders" aria-hidden="true"></span></span>
        </a>
      </li>
      <li>
        <a href="#integrations">
          <span class="title">Integrations<span class="leaders" aria-hidden="true"></span></span>
        </a>
      </li>
    </ol>
  </li>
</ol>

<h2 id="overview">Overview</h2>
<p>Compendium is a comprehensive CI/CD suite designed to streamline your development and deployment workflows. It integrates seamlessly with your existing tools and automates key processes to increase efficiency.</p>

<h3 id="compendium">What is Compendium?</h3>
<p>Compendium is a modular CI/CD product that centralizes automation, monitoring, and deployment processes into one cohesive platform. It is built to handle complex workflows and offers scalability across various environments; while remaining simple, comprehensive, and user friendly.</p>

<h3 id="capabilities">What are Compendium's capabilities?</h3>
<p>The suite offers features including:</p>
<ul>
  <li>Continuous Integration and *Deployment</li>
  <li>Automated Testing and Code Quality Analysis</li>
  <li>*Monitoring and Logging</li>
  <li>Scalability and Customizability</li>
</ul>

<h3 id="who">Who is Compendium for?</h3>
<p>Designed for development teams, DevOps professionals, organizations, and individuals looking to optimize their software development lifecycle, Compendium caters to all ranges of development proffesionals.</p>

<h2 id="technical">Technical Details</h2>
<p>This section outlines the technical aspects of Compendium, including installation, configuration, and integration details. For further information, visit the <a href="https://github.com/parkermmr/Compendium" target="_blank">GitHub repository</a>.</p>

<h3 id="architecture">Architecture</h3>

<h3 id="integrations">Integrations</h3>
