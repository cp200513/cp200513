## Hi there 👋

<!--
**cp200513/cp200513** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
<script>
  // Detect user's color scheme preference
  const isDarkMode = window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches;

  // Select the element where you want to display the images
  const readmeContent = document.getElementById('readme-content');

  if (isDarkMode) {
    // If dark mode is active, insert the dark version of the 3D graph
    readmeContent.innerHTML = `
      ![](https://raw.githubusercontent.com/cp200513/cp200513/profile-3d-contrib/profile-night-rainbow.svg)
    `;
  } else {
    // If light mode is active, insert the light version of the 3D graph
    readmeContent.innerHTML = `
      ![](https://raw.githubusercontent.com/cp200513/cp200513/profile-3d-contrib/profile-gitblock.svg)
    `;
  }
</script>

<!-- Where the content will be rendered -->
<div id="readme-content"></div>


![](profile-3d-contrib/profile-night-rainbow.svg)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/cp200513/cp200513/profile-3d-contrib/profile-night-rainbow.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/cp200513/cp200513/profile-3d-contrib/profile-gitblock.svg" />
  <img alt="profile images" src="https://raw.githubusercontent.com/cp200513/cp200513/profile-3d-contrib/profile-gitblock.svg" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/cp200513/cp200513/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/cp200513/cp200513/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/cp200513/cp200513/output/github-snake.svg" />
</picture>
