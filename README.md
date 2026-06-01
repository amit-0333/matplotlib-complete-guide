<div align="center">

```
███╗   ███╗ █████╗ ████████╗██████╗ ██╗      ██████╗ ████████╗██╗     ██╗██████╗ 
████╗ ████║██╔══██╗╚══██╔══╝██╔══██╗██║     ██╔═══██╗╚══██╔══╝██║     ██║██╔══██╗
██╔████╔██║███████║   ██║   ██████╔╝██║     ██║   ██║   ██║   ██║     ██║██████╔╝
██║╚██╔╝██║██╔══██║   ██║   ██╔═══╝ ██║     ██║   ██║   ██║   ██║     ██║██╔══██╗
██║ ╚═╝ ██║██║  ██║   ██║   ██║     ███████╗╚██████╔╝   ██║   ███████╗██║██████╔╝
╚═╝     ╚═╝╚═╝  ╚═╝   ╚═╝   ╚═╝     ╚══════╝ ╚═════╝    ╚═╝   ╚══════╝╚═╝╚═════╝ 
```

### 📊 Matplotlib Complete Guide

> A complete hands-on Matplotlib repository — from basic 2D plots to advanced 3D visualizations, subplots, heatmaps & Pandas plotting using Python.

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

</div>

---

## 📌 About

This is my **complete Matplotlib learning journal** — covering all major plot types, customization techniques, and real-world data visualization using IPL, stock, and statistical datasets.

Built to master:
- Plotting numerical and categorical data effectively
- Customizing plots — colors, markers, linestyles, legends, grids
- Building subplots and multi-panel figures
- Advanced 3D plots — scatter, line, surface
- Heatmaps, contour plots, and annotated charts
- Plotting directly from Pandas DataFrames

---

## 📚 Topics Covered

### Session 23 — 🟢 Matplotlib Basics

| # | Topic | Description |
|---|-------|-------------|
| 01 | 📈 2D Line Plot | Simple & multiple line plots, labels, titles, colors, markers |
| 02 | 🎨 Plot Customization | Colors (hex), linestyle, linewidth, markersize, legend location |
| 03 | 🔢 Axis Limiting | `plt.xlim`, `plt.ylim` — controlling axis ranges |
| 04 | 🔲 Grid | Adding grid lines to plots |
| 05 | 🔵 Scatter Plots | `plt.scatter` vs `plt.plot('o')`, size, color, cmap, marker |
| 06 | 📊 Bar Charts | Vertical, horizontal, multiple & stacked bar charts |
| 07 | 📉 Histograms | Bins, log scale, frequency distribution |
| 08 | 🥧 Pie Charts | Single & multiple pie charts, labels, percentages |

### Session 24 — 🔵 Advanced Matplotlib

| # | Topic | Description |
|---|-------|-------------|
| 09 | 🌈 Colored Scatter Plots | `cmap`, `alpha`, `colorbar` — coloring by category |
| 10 | 📐 Plot Size | `figsize` — controlling figure dimensions |
| 11 | 🏷️ Annotations | `plt.text()` — adding labels and text to plots |
| 12 | ➖ Reference Lines | `plt.axhline`, `plt.axvline` — horizontal & vertical lines |
| 13 | 🗂️ Subplots | `plt.subplots`, `fig.add_subplot` — multi-panel figures |
| 14 | 🌐 3D Scatter Plots | `projection='3d'` — 3D scatter analysis |
| 15 | 📏 3D Line Plots | 3D line visualization with `ax.plot3D` |
| 16 | 🏔️ 3D Surface Plots | `ax.plot_surface` with viridis colormap |
| 17 | 🗺️ Contour Plots | `ax.contour` & `ax.contourf` — 2D surface visualization |
| 18 | 🔥 Heatmaps | `plt.imshow` — grid-based heatmaps with colorbar |
| 19 | 🐼 Pandas Plot() | Plotting directly from Series & DataFrame using `.plot()` |

---

## 🗂️ Repository Structure

```bash
matplotlib-colab/
│
├── 📓 session-23-matplotlib.ipynb       # Basics — line, scatter, bar, histogram, pie
├── 📓 session-24-advanced-matplotlib.ipynb  # Advanced — 3D, subplots, heatmap, pandas plot
│
├── 📂 datasets/
│   ├── sharma-kohli.csv                 # Rohit Sharma & Virat Kohli IPL career data
│   ├── batter.csv                       # IPL batters stats
│   ├── batsman_season_record.csv        # Season-wise batting records
│   ├── vk.csv                           # Virat Kohli match data
│   ├── IPL_Ball_by_Ball_2008_2022.csv   # Ball-by-ball IPL delivery data
│   └── iris.csv                         # Iris flower dataset
│
└── 📄 README.md
```

---

## ⚙️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/amit-0333/matplotlib-colab.git

# 2. Navigate into the folder
cd matplotlib-colab

# 3. Install dependencies
pip install matplotlib numpy pandas seaborn jupyter

# 4. Launch Jupyter Notebook
jupyter notebook

# Or open directly in Google Colab
```

---

## 🧪 Real-World Datasets Used

| Dataset | Used For |
|---------|----------|
| `sharma-kohli.csv` | Line plot — Rohit vs Virat career comparison |
| `batter.csv` | Scatter plot — Avg vs Strike Rate analysis |
| `batsman_season_record.csv` | Multiple & stacked bar charts |
| `vk.csv` | Histogram — Virat Kohli match runs distribution |
| `IPL_Ball_by_Ball_2008_2022.csv` | Heatmap — boundary analysis per over |
| `iris.csv` | Colored scatter — sepal vs petal by species |
| `tips` (seaborn) | Scatter with size & cmap, Pandas plot |
| `weekly_stocks.csv` | Line plot — MSFT, FB, AAPL stock trends |

---

## 🧩 My Approach to Every Plot

```
1. 📖 Understand what type of data the plot is best suited for
2. 🔨 Build the basic version first
3. 🎨 Customize — colors, markers, labels, legend, grid
4. 📊 Apply to a real dataset
5. ✅ Note the use case — univariate / bivariate / categorical / numerical
```

---

## 🎯 Learning Goals

- [x] Plot 2D line charts with full customization
- [x] Build scatter plots — simple, colored, sized, annotated
- [x] Create bar charts — vertical, horizontal, multiple, stacked
- [x] Plot histograms with bins and log scale
- [x] Build pie charts — single and multiple
- [x] Control axis limits and add grids
- [x] Build multi-panel figures with subplots
- [x] Create 3D scatter, line & surface plots
- [x] Build contour plots and heatmaps
- [x] Plot directly from Pandas DataFrames using `.plot()`
- [ ] Explore more chart types — boxplot, violinplot
- [ ] Build a complete data visualization case study

---

## 🛠️ Tech Stack

- 🐍 **Python** — Core programming language
- 📊 **Matplotlib** — Primary plotting library
- 🔢 **NumPy** — Numerical data for plots
- 🐼 **Pandas** — DataFrame-based plotting
- 🎨 **Seaborn** — Dataset loading & styling
- 📓 **Jupyter / Google Colab** — Interactive notebooks

---

## 🙏 Credits & Acknowledgement

> This repository is built while learning from **[Campus X](https://www.youtube.com/@campusx-official)** — an amazing free Data Science education channel.
> Notebooks are based on class materials from Campus X. All credit for the curriculum and teaching goes to them.
> I've added my own notes, practice, and experiments on top of the class content.

---

## 👨‍💻 Author

**Amit Kumar**

[![GitHub](https://img.shields.io/badge/GitHub-amit--0333-181717?style=flat&logo=github)](https://github.com/amit-0333)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Amit%20Kumar-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/amit-kumar-a62a3640a/)
[![Kaggle](https://img.shields.io/badge/Kaggle-amitkumar038975-20BEFF?style=flat&logo=kaggle)](https://www.kaggle.com/amitkumar038975)

---

<div align="center">

> 📝 *This repository is continuously updated as I learn new visualization techniques.*

⭐ **Star this repo if it helped you learn Matplotlib!**

</div>
