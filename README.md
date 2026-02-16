# 💫 About Me:
Passionate Programmer from India  

<div align="center">
  <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="600" height="300"/>
</div>

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rathod-pavan-kumar/) 
[![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/RathodPavan0007) 
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://www.youtube.com/@rathodpavan0007) 
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:rathodpavan2292@gmail.com)

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-%233776AB.svg?style=flat&logo=python&logoColor=white) 
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E) 
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white) 
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white) 
![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=flat&logo=node.js&logoColor=white) 
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=flat&logo=google-cloud&logoColor=white)
![Appwrite](https://img.shields.io/badge/Appwrite-F02E65.svg?style=flat&logo=appwrite&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=flat&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=flat&logo=figma&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=flat&logo=Canva&logoColor=white)

## 🤖 AI & Machine Learning:
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=flat&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-%23F7931E.svg?style=flat&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=flat&logo=plotly&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-2E77BC.svg?style=flat&logo=chainlink&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-%23FFCC00.svg?style=flat&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991.svg?style=flat&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4.svg?style=flat&logo=google&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000.svg?style=flat&logo=ollama&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-1E90FF.svg?style=flat&logo=databricks&logoColor=white)
![Vector Search](https://img.shields.io/badge/pgvector-336791.svg?style=flat&logo=postgresql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B.svg?style=flat&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=flat&logo=docker&logoColor=white)


# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=rathod-0007&theme=dark&hide_border=true&include_all_commits=true&count_private=true)
![](https://nirzak-streak-stats.vercel.app/?user=rathod-0007&theme=dark&hide_border=true)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=rathod-0007&theme=dark&hide_border=true&include_all_commits=true&count_private=true&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=rathod-0007&theme=dark&no-frame=true&no-bg=true&margin-w=4)


---

[![](https://visitcount.itsvg.in/api?id=rathod-0007&icon=0&color=12)](https://visitcount.itsvg.in)

[![@rathod0007's Holopin board](https://holopin.me/rathod0007)](https://holopin.io/@rathod0007)

name: 🐍 Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"   # Runs daily at midnight UTC
  workflow_dispatch:

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: Generate Snake SVG
        uses: Platane/snk@v3
        with:
          github_user_name: rathod-0007
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


<h1 align="center">Show some ❤️ by starring some of the repositories!</h1>
