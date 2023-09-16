### Hlw there 👋

<!--
**CodeCraftsman0/CodeCraftsman0** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# 🏄‍♂️ CodeCraftsman0
 
**`Digit CodeCraftsman0 (Frontend Developer)`**

Hello! I'm saurabh and I'm passionate about bringing digital experiences to life through web development. As a front-end developer, I specialize in creating the visual and interactive elements of websites and web applications that users see and interact with directly. What sets me apart as a front-end developer is my dedication to staying up-to-date with the latest technologies and design trends. I have a deep understanding of HTML, CSS, and JavaScript, and I love exploring WordPress, Bootstrap, and Ajax to build responsive, efficient, and dynamic user interfaces. "[CodeCraftsman0][youtube]".






<!--header-->
<table>
  <tr><td colspan="2"><a href="/README.md#-plugins">← Back to plugins index</a></td></tr>
  <tr><th colspan="2"><h3>✨ Stargazers</h3></th></tr>
  <tr><td colspan="2" align="center"><p>This plugin displays stargazers evolution across affiliated repositories.</p>
</td></tr>
  <tr><th>⚠️ Disclaimer</th><td><p>This plugin is not affiliated, associated, authorized, endorsed by, or in any way officially connected with <a href="https://github.com">GitHub</a>.
All product and company names are trademarks™ or registered® trademarks of their respective holders.</p>
</td></tr>
  <tr>
    <th rowspan="3">Supported features<br><sub><a href="metadata.yml">→ Full specification</a></sub></th>
    <td><a href="/source/templates/classic/README.md"><code>📗 Classic template</code></a> <a href="/source/templates/repository/README.md"><code>📘 Repository template</code></a></td>
  </tr>
  <tr>
    <td><code>👤 Users</code> <code>👥 Organizations</code> <code>📓 Repositories</code></td>
  </tr>
  <tr>
    <td><code>🔑 (scopeless)</code> <code>🗝️ plugin_stargazers_worldmap_token</code> <code>read:org (optional)</code> <code>read:user (optional)</code> <code>read:packages (optional)</code> <code>repo (optional)</code></td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <details open><summary>Classic charts</summary><img src="https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.stargazers.svg" alt=""></img></details>
      <details><summary>Graph charts</summary><img src="https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.stargazers.graph.svg" alt=""></img></details>
      <details open><summary>Worldmap</summary><img src="https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.stargazers.worldmap.svg" alt=""></img></details>
      <img width="900" height="1" alt="">
    </td>
  </tr>
</table>
<!--/header-->

## 🗝️ Obtaining a Google Maps API token

Some features like `plugin_stagazers_worldmap` require a Google Geocoding API token.
Follow instructions from their [documentation](https://developers.google.com/maps/documentation/geocoding/get-api-key) for more informations.

> 💳 A billing account is required to get a token. However a recurring [monthly credit](https://developers.google.com/maps/billing-credits#monthly) is offered which means you should not be charged if you don't exceed the free quota.
>
> It is advised to set the quota limit at 1200 requests per day
>
> Use at your own risk, *metrics* and its authors cannot be held responsible for anything charged.

## ➡️ Available options

<!--options-->
<table>
  <tr>
    <td align="center" nowrap="nowrap">Option</i></td><td align="center" nowrap="nowrap">Description</td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_stargazers</code></h4></td>
    <td rowspan="2"><p>Enable stargazers plugin</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>boolean</code>
<br>
<b>default:</b> no<br></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_stargazers_days</code></h4></td>
    <td rowspan="2"><p>Time range</p>
<p>If set to <code>0</code> the account registration date will be used.</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>number</code>
<i>(0 ≤
𝑥)</i>
<br>
<b>zero behaviour:</b> see description</br>
<b>default:</b> 14<br></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_stargazers_charts</code></h4></td>
    <td rowspan="2"><p>Charts</p>
<p>It includes total number of stargazers evolution, along with the number of new stars per day over the last two weeks.</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>boolean</code>
<br>
<b>default:</b> yes<br></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_stargazers_charts_type</code></h4></td>
    <td rowspan="2"><p>Charts display type</p>
<ul>
<li><code>classic</code>: <code>&lt;div&gt;</code> based charts, simple and lightweight</li>
<li><code>graph</code>: <code>&lt;svg&gt;</code> based charts, smooth</li>
</ul>
<blockquote>
<p>⚠️ <code>chartist</code> option has been deprecated and is now equivalent to <code>graph</code></p>
</blockquote>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap">🌐 Web instances must configure <code>settings.json</code>:
<ul>
<li><i>metrics.npm.optional.d3</i></li>
</ul>
<b>type:</b> <code>string</code>
<br>
<b>default:</b> classic<br>
<b>allowed values:</b><ul><li>classic</li><li>graph</li><li>chartist</li></ul></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_stargazers_worldmap</code></h4></td>
    <td rowspan="2"><p>Stargazers worldmap</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap">🌐 Web instances must configure <code>settings.json</code>:
<ul>
<li><i>metrics.api.google.maps</i></li>
<li><i>metrics.npm.optional.d3</i></li>
</ul>
<b>type:</b> <code>boolean</code>
<br>
<b>default:</b> no<br></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_stargazers_worldmap_token</code></h4></td>
    <td rowspan="2"><p>Stargazers worldmap token</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap">🔐 Token<br>
<b>type:</b> <code>token</code>
<br></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_stargazers_worldmap_sample</code></h4></td>
    <td rowspan="2"><p>Stargazers worldmap sample</p>
<p>Use this setting to randomly sample and limit your stargazers.
Helps to avoid consuming too much Google Geocoding API requests while still being representative.</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>number</code>
<i>(0 ≤
𝑥)</i>
<br>
<b>zero behaviour:</b> disable</br>
<b>default:</b> 0<br></td>
  </tr>
</table>
<!--/options-->

## ℹ️ Examples workflows

<!--examples-->
```yaml
name: Using classic charts
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.stargazers.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ""
  plugin_stargazers: yes

```
```yaml
name: Using graph charts
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.stargazers.graph.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ""
  plugin_stargazers: yes
  plugin_stargazers_charts_type: graph

```
```yaml
name: With worldmap
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.stargazers.worldmap.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ""
  plugin_stargazers: yes
  plugin_stargazers_charts: no
  plugin_stargazers_worldmap: yes
  plugin_stargazers_worldmap_token: ${{ secrets.GOOGLE_MAP_TOKEN }}
  plugin_stargazers_worldmap_sample: 200

```
<!--/examples-->











<a href="https://www.facebook.com/saurabhsantraiamok/">
  <img src="https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white" alt="Facebook Logo">
</a>
<a href="https://www.linkedin.com/in/saurabh-santra-4b2b0a164/">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Logo">
</a>
<a href="https://www.youtube.com/c/Artonad">
  <img src="https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white" alt="YouTube Logo">
</a>
<a href="https://profile.indeed.com/?hl=en_IN&co=IN&from=gnav-homepage&_ga=2.255864898.899499604.1694632849-708376156.1694138823">
  <img src="https://img.shields.io/badge/indeed-003A9B?style=for-the-badge&logo=indeed&logoColor=white" alt="Indeed Logo">
</a>

### 🧰 Languages and Tools


![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-%23117AC9.svg?style=for-the-badge&logo=WordPress&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
<img align="left" alt="NodeJS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" />
<br />

<p align="left"> <img src="https://komarev.com/ghpvc/?username=codecraftsman0&label=Profile%20views&color=0e75b6&style=flat" alt="codecraftsman0" /> </p>
<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=codecraftsman0&show_icons=true&locale=en&layout=compact" alt="codecraftsman0" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=codecraftsman0&show_icons=true&locale=en" alt="codecraftsman0" /></p>



<details>
 <summary><h3>👨‍💻 Saurabh Coding Journey</h3></summary>
    HI ALL, I COMPLETED A DIPLOMA FROM SILIGURI GOVERNMENT POLYTECHNIC COLLEGE AND LATER I COMPLETED MY BACHELOR'S DEGREE FROM CAMELLIA SCHOOL OF ENGINEERING AND TECHNOLOGY COLLEGE AFTER THAT, I STARTED MY JOURNEY IN WEB DEVELOPMENT AND I WANT TO TAKE CARE OF IT. I SPECIALIZE IN FRONT-END DEVELOPMENT AND AM EXPERIENCED WITH ALL STAGES OF THE DEVELOPMENT CYCLE FOR DYNAMIC WEB PROJECTS. WELL-VERSED IN NUMEROUS PROGRAMMING LANGUAGES INCLUDING CSS, HTML, JAVASCRIPT, BOOTSTRAP, PHP, MYSQL, JQUERY, AJAX, NODE JS, AND WORDPRESS AND I'M LOOKING FOR A JOB AND READY TO FACE NEW CHALLENGES.

[YouTube]: https://www.youtube.com/@Artonad

<h3 align="left">Support:</h3>
<p><a href="https://www.buymeacoffee.com/CodeCraftsman0"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="CodeCraftsman0" /></a><a href="https://ko-fi.com/CodeCraftsman0"> <img align="left" src="https://cdn.ko-fi.com/cdn/kofi3.png?v=3" height="50" width="210" alt="CodeCraftsman0" /></a></p><br><br>



