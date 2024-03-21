<!--타이틀 부분-->
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=wave&color=A3DCBE&height=300&section=header&text=capsule%20render&fontSize=90" />
</div>

<!--내용 부분-->
<h3 align="center">✨ Tech Stack ✨</h3>
<div align="center">
  <img src="https://img.shields.io/badge/react-20232a.svg?style=for-the-badge&logo=react&logoColor=61DAFB" />&nbsp
  <img src="https://img.shields.io/badge/javascript-F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=20232a" />&nbsp
  <img src="https://img.shields.io/badge/html5-E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" />&nbsp
</div>

<div align="center">
  <img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=ffd35b" />&nbsp
  <img src="https://img.shields.io/badge/tailwindcss-1daabb.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/css3-1572B6.svg?style=for-the-badge&logo=css3&logoColor=white" />&nbsp
</div>

<br>

<div align="center">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />&nbsp
  <img src="https://img.shields.io/badge/pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/numpy-4d77cf.svg?style=for-the-badge&logo=numpy&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/Matplotlib-11557c.svg?style=for-the-badge&logo=Matplotlib&logoColor=white" />&nbsp
</div>

<br>

<h3 align="center">📚 Studying 📚</h3>
<div align="center">
  <img src="https://img.shields.io/badge/typescript-007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/Recoil-3578E5?style=for-the-badge&logo=recoil&logoColor=white" />&nbsp
</div>

<br>

<h3 align="center">🛠 Tools 🛠</h3>
<div align="center">
  <img src="https://img.shields.io/badge/git-F05033.svg?style=for-the-badge&logo=git&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logo=github&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/Notion-F3F3F3.svg?style=for-the-badge&logo=notion&logoColor=black" />&nbsp
</div>

<div align="center">
  <img src="https://img.shields.io/badge/adobe%20photoshop-08253c.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=37abff" />&nbsp
  <img src="https://img.shields.io/badge/figma-F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white" />&nbsp
</div>

<br>

<div align="center">
  <img src="https://img.shields.io/badge/VSCode-2C2C32.svg?style=for-the-badge&logo=visual-studio-code&logoColor=22ABF3" />&nbsp
  <img src="https://img.shields.io/badge/jupyter-2C2C32.svg?style=for-the-badge&logo=jupyter&logoColor=F37726" />&nbsp
<!--   <img src="https://img.shields.io/badge/Colab-2C2C32.svg?style=for-the-badge&logo=googlecolab&logoColor=F9AB00" />&nbsp -->
</div>

<br>

<h3 align="center">📫 Contact 📫</h3>
<div align="center">
  <a href="https://velog.io/@oka1313">
    <img src="https://img.shields.io/badge/Velog-1EBC8F?style=for-the-badge&logo=velog&logoColor=white" />&nbsp
  </a>
  <a href="mailto:oka1313@gmail.com">
    <img
      src="https://img.shields.io/badge/oka1313@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>&nbsp
  </a>
</div>


<script>
  import { checkReversal } from "../../src/util";

const render = (reversal, color, height) => {
  reversal = checkReversal(reversal);
  const width = 854;

  const PATHS = [
    `M52.8,-67C68,-61.6,79.7,-45.6,82.5,-28.7C85.4,-11.8,79.5,6,71.4,20.8C63.2,35.5,53,47.1,40.7,53.3C28.5,59.4,14.2,60,-2.1,63C-18.5,65.9,-37,71.2,-52.3,66C-67.6,60.9,-79.7,45.4,-81.5,29C-83.2,12.7,-74.6,-4.4,-68.7,-22.2C-62.8,-40.1,-59.5,-58.7,-48.4,-65.4C-37.4,-72.2,-18.7,-67.1,0,-67.1C18.8,-67.2,37.6,-72.4,52.8,-67Z`,
    `M42.3,-55.2C55.2,-48.7,66.6,-37,69.3,-23.7C72,-10.4,66,4.6,58.3,16.1C50.6,27.6,41.2,35.6,31.1,43.9C21.1,52.1,10.6,60.6,-1.3,62.5C-13.2,64.3,-26.4,59.4,-37.6,51.5C-48.8,43.6,-57.9,32.7,-61,20.5C-64.1,8.3,-61.1,-5.3,-57.9,-19.9C-54.7,-34.6,-51.3,-50.3,-41.6,-57.8C-32,-65.3,-16,-64.7,-0.7,-63.7C14.6,-62.8,29.3,-61.6,42.3,-55.2Z`,
    `M49.2,-63.6C62.2,-58.3,70.1,-41.8,74.6,-24.9C79.1,-8.1,80.3,9.2,76.5,26.2C72.8,43.2,64.2,59.9,50.7,68.4C37.1,76.9,18.5,77.2,2.3,74.1C-13.9,70.9,-27.9,64.2,-41.2,55.6C-54.6,47.1,-67.4,36.6,-74.5,22.4C-81.7,8.2,-83.2,-9.7,-74.7,-20.8C-66.3,-31.9,-47.9,-36.3,-33.8,-41.2C-19.7,-46.2,-9.8,-51.8,4.1,-57.5C18.1,-63.1,36.2,-68.9,49.2,-63.6Z`,
  ];

  return `
    <g transform="translate(${width / 2}, ${height / 2})">
      <path id="myPath" fill="${color}" d="${PATHS[0]}" ${reversal}>
        <animate attributeName="d" dur="10s" values="
          ${PATHS.join("; ")};
          ${PATHS[0]}"
          repeatCount="indefinite"
        />
      </path>
    </g>`;
};

export default render;
</script>
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=gusdk45&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=gusdk45&layout=compact)
