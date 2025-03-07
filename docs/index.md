
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
    <a href="#Heading1">
      <span class="title">Heading 1<span class="leaders" aria-hidden="true"></span></span>
    </a>
        <ol role="list">
            <li>
                <a href="#SubHeading1">
                            <span class="title">Sub-Heading 1<span class="leaders" aria-hidden="true"></span>
                </a>
            </li>
        </ol>
    </li>
</ol>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-0pky">Component</th>
    <th class="tg-0pky">Purpose</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-0pky">compendium/jobs/docker/build@v1</td>
    <td class="tg-0pky">Build from Dockerfile and publish to registry.</td>
  </tr>
  <tr>
    <td class="tg-0pky">compendium/jobs/java/lint-checkstyle@v1</td>
    <td class="tg-0pky">Lint using CheckStyle linting for java.</td>
  </tr>
  <tr>
    <td class="tg-0pky">compendium/jobs/java/gradle/build@v1</td>
    <td class="tg-0pky">Build a JAR from java source with gradle.</td>
  </tr>
  <tr>
    <td class="tg-0pky">compendium/jobs/java/maven/compile@v1</td>
    <td class="tg-0pky">Compile java code with maven.</td>
  </tr>
  <tr>
    <td class="tg-0pky">compendium/jobs/java/maven/test-junit@v1</td>
    <td class="tg-0pky">Test java code with maven junit tests.</td>
  </tr>
  <tr>
    <td class="tg-0pky">compendium/jobs/java/maven/javadocs-publish@v1</td>
    <td class="tg-0pky">Publish javadocs with Github pages and maven.</td>
  </tr>
  <tr>
    <td class="tg-0pky">compendium/jobs/release/deploy-tag@v1</td>
    <td class="tg-0pky">Deploy a tag to GitHub on success of pipeline.</td>
  </tr>
  <tr>
    <td class="tg-0pky">compendium/jobs/release/publish-docs@v1</td>
    <td class="tg-0pky">Publish mkdocs with GitHub pages.</td>
  </tr>
  <tr>
    <td class="tg-0pky">compendium/jobs/python/lint-flake8@v1</td>
    <td class="tg-0pky">Lint python code to flake8, black, and isort standards.</td>
  </tr>
  <tr>
    <td class="tg-0pky">compendium/jobs/python/poetry-pytest@v1</td>
    <td class="tg-0pky">Test python code using poetry as a package manager.</td>
  </tr>
  <tr>
    <td class="tg-0pky">compendium/jobs/security/secure@v1</td>
    <td class="tg-0pky">CodeQL security and vulnerability scan. </td>
  </tr>
</tbody></table>