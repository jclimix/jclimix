# 🎮 JCLimix | GitHub Readme

![Profile Banner](https://i.ibb.co/F87p8DQ/kirby-custom-sprite-preview-by-hartflip0218-dcmbetv.gif)

## 👋 About Me
Hi there! I'm **James Ezeilo**, a passionate creator who loves using coding and sports analytics to build fun, meaningful projects that *change the game*.

Whether it’s making interactive dashboards, predictive models, or visualizing complex data — I'm always exploring new ways to combine **technology**, **sports**, and **healthcare** into impactful tools.

- 🔭 Passionate about **sports analytics** and **healthcare innovation**  
- 💬 Open to feedback, collabs, or just nerding out about data!  
- 📫 Reach me: [jmge.work@gmail.com](mailto:jmge.work@gmail.com)  
- ⚡ Fun Fact: I once used data analysis to win a fantasy sports league. (Also... Smash Bros main = Kirby.)

---

# 🏥📊 PediaMetrics | Pediatric Healthcare Data Automation

**PediaMetrics** is a full-stack pediatric healthcare analytics platform designed to automate patient triage, diagnostics, lab result simulations, and treatment recommendations — using **realistic, simulated data**.

Built for healthcare research and education, it enables fast, structured analysis of pediatric visits and integrates directly with Tableau dashboards for live reporting.

### 🚀 [Try It Here](https://pediametrics.universe-j.com/)

## 📋 Key Features
- **Simulated Patient Profiles**: Randomized demographics, vitals, BMI categories, and activity levels tailored by age and gender.
- **Triage & Initial Evaluation**: Assigns realistic vitals (heart rate, respiratory rate, blood pressure, temperature) dynamically.
- **Lab Test Simulation (Pre-Alpha)**: Generates pediatric-specific blood test results (lead, hemoglobin, glucose, etc.).
- **Disease Prediction Engine**: Matches symptoms to a disease database using a weighted scoring system to suggest diagnoses and treatments.
- **Visit Summary Generator**: Produces downloadable structured PDF reports summarizing patient demographics, vitals, and recommended care.
- **Continuous Data Flow**: Cron jobs simulate patient visits every 2 hours from 7 AM–4 PM, Monday–Friday, mimicking real pediatric clinic activity.
- **Live Tableau Integration**: Patient data is connected via Google Drive for dynamic dashboards and reporting.

## 🛠️ Tech Stack
- **Backend**: Python, Flask
- **Data Processing**: Pandas, NumPy
- **Cloud Storage**: AWS S3 (via Boto3), Google Drive API (for Tableau integration)
- **Automation**: Apache Airflow, Cron jobs
- **Logging**: Loguru

## 📂 Data Storage & Processing
- Patient visit records stored securely on **Amazon S3** and **Google Drive**.
- **Scheduled scripts** clean, process, and upload new patient data throughout the workweek.
- **Structured logging** tracks all data generation and processing activities for auditing and debugging.

## ❗ Important Note
> All patient data used in PediaMetrics is **randomly generated and entirely fictional**. No real patient information is stored or presented.

## 🔧 Behind the Scenes
- `patientGenerator.py`: Creates new patient profiles.
- `patientTriage.py`: Assigns triage evaluations.
- `labGenerator.py`: Simulates lab test results.
- `patientResults.py`: Predicts disease likelihoods.
- `patientSummary.py`: Formats visit summaries into PDFs.

## 🏁 Summary
PediaMetrics automates the end-to-end lifecycle of pediatric healthcare data generation, triage evaluation, diagnosis prediction, and reporting — offering an innovative, safe environment for healthcare analytics based on simulated patient records.

---

# 🏀📚 HooperLabs | Basketball Data Innovation Platform

**HooperLabs** is a full-scale basketball analytics platform combining **automated data pipelines**, **custom web apps**, and **deep statistical analysis** — designed to transform raw basketball data into actionable insights.

Built on a custom, scalable infrastructure, HooperLabs empowers players, fans, analysts, and researchers to dive deeper into the game like never before.

### 🚀 [Explore HooperLabs](https://hooper-labs.com)

## 🏗️ Platform Architecture
- **Web Application Server**:  
  Linux VPS hosting multiple Flask-based basketball analytics web apps, optimized via NGINX reverse proxy for security and performance.
- **Database Server (HooperData)**:  
  Dedicated PostgreSQL server acting as the central data hub, avoiding API rate limits and ensuring reliable access to high-quality basketball stats.
- **Automated ETL System**:  
  Python scripts extract, clean, and load data from Basketball Reference into the database via cron jobs — keeping stats current without manual updates.
- **Web Access & API Access**:  
  Each web app is independently maintained with automatic GitHub deployment pipelines.

## 🛠️ Core Technical Skills Behind HooperLabs
### Data Analysis & Tools
- Python (Pandas, NumPy), Web Scraping (BeautifulSoup)
- Statistical Modeling & Advanced Analytics
- Data Visualization (Matplotlib, Plotly)
- Custom Basketball Metrics Development

### Data Engineering
- ETL Pipeline Development (Python + Cron)
- PostgreSQL Database Design & Optimization
- SQL Query Optimization and Automation

### Development & DevOps
- Flask Web Development (Backend)
- HTML, CSS, JavaScript (Frontend)
- Linux Server Administration
- NGINX Configuration
- GitHub Automated Deployment

## 🔬 Featured Projects
- **🏀🧬 HooperDNA**: Predict the NBA player most statistically similar to a college prospect.
- **🏀🐐 NBA GOAT Calculator**: Customize your own "Top 100" NBA player rankings based on different statistical weights.
- *(More web apps in development!)*

## 🎯 HooperLabs Mission
> To revolutionize basketball analysis by combining automated data engineering with innovative, interactive analytics tools — making deep basketball insights accessible to everyone.

---

# 🛠️ Technical Skills
- **Languages:** Python, SQL, HTML, CSS
- **Frameworks:** Flask, Django
- **Data Tools:** Pandas, NumPy, DuckDB, BeautifulSoup
- **Cloud & DevOps:** AWS S3, Airflow, Docker
- **Other:** Git, VS Code

---

# 📈 GitHub Stats
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jclimix&show_icons=true&theme=radical)

---

# 📫 Connect With Me
- [LinkedIn](https://www.linkedin.com/in/james-ezeilo/)
- [More About Me](https://link.me/jmge.work)
