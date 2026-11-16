# Data Visualization and Storytelling

## Project Overview
This repository tells a four-part business story on e-commerce growth, conversion gaps, regional drivers, and discount margin protection using Matplotlib and Seaborn.

## Repository Structure
- `README.md`: Project overview, narrative summary, and usage guide
- `requirements.txt`: Required Python dependencies
- `data/ecommerce_story_data.csv`: Monthly revenue, order volume, and device conversion dataset
- `notebooks/data_storytelling.ipynb`: Jupyter Notebook generating all 4 storytelling visualizations
- `docs/storytelling_presentation.pdf`: Slide-style presentation summarizing key findings and strategic recommendations

## Key Findings & Narrative
1. **Revenue Growth**: Monthly revenue tripled from $42K in January to $128K in December, led by a Q4 holiday surge.
2. **Mobile Conversion Gap**: Desktop converts ~1.5 percentage points higher than Mobile every month, pointing to mobile checkout friction.
3. **Regional Concentration**: North America ($365K) and Europe ($240K) drive 70% of annual revenue, with Asia-Pacific ($185K) emerging rapidly.
4. **Margin Protection**: Discounts above 20% erode net profit margins below 22%, establishing 20% as the optimal promotional cap.

## How to Run
1. Clone the repository:
   `git clone https://github.com/adhikarysayantani7-tony/data-visualization-and-storytelling.git`
2. Install dependencies:
   `pip install -r requirements.txt`
3. Open the notebook:
   `jupyter notebook notebooks/data_storytelling.ipynb`
