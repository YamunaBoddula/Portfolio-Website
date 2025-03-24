# Portfolio-Website
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
    <title>Yaswanth Sai</title>
</head>

<body>
    <!-- The video -->
    <video autoplay muted loop id="myVideo">
        <source src="img/bg.mp4" type="video/mp4">
        The video could not be play in browser
    </video>

    <!-- Navigation Bar -->
    <header>
        <nav>
            <b>Yaswanth Sai</b>
            <div class="hamburger" id="hamburger">
                <div></div>
                <div></div>
                <div></div>
            </div>
            <ul id="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="https://1drv.ms/b/c/d2204435c6b0ad92/EWITlaL28jJBqcAZyulRIt0B2MzuGzVxBcN_XiG0hE5AkQ?e=5Jfrbw" target="_blank">Resume</a></li>
                <li><a href="#certificates">Certificates</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="hero">
        <div class="hero-content">
            <h1>Hello, I'm Yaswanth Sai</h1>
            <p>Data Analyst | Power BI Expert | Excel Specialist</p>
            <div id="social-links">
                <a href="https://www.linkedin.com/in/abbaraju-v-n-s-yaswanth-sai-b6b660234/" id="linkedin"
                    target="_blank">
                    <img src="img/linkedin.png" alt="">LinkedIn Profile
                </a>
                <a href="https://github.com/YaswanthSai2807" id="github" target="_blank">
                    <img src="img/github.png" alt="">GitHub Profile
                </a>
            </div>
        </div>
    </section>

    <!--Skills&About-->
    <section class="container" id="about">
        <h2 id="title">About Me</h2>
        <div class="about-container">
            <img src="img/avatar.png" alt="profilepic" id="profilepic">
            <div class="about-text" id="about-text">
                <h2>Abbaraju V N S Yaswanth Sai</h2>
                <b>Email:</b><a href="mailto:saiyaswanthabbaraju@gmail.com">saiyaswanthabbaraju@gmail.com</a><br>
                <b>Mobile:</b><a href="tel:+91 8247049609">+91 8247049609</a>

                <p id="about_p">Passionate data analyst with a strong background in data visualization, cleaning, and
                    analysis. My goal is to provide actionable insights that help businesses make data-driven decisions.
                    Driven to learn quickly, advance computer proficiency and training in industry operations. Solid
                    background in field and office settings supporting team needs. Flexible and hardworking team player
                    focused on boosting productivity and performance with conscientious and detail-oriented approaches.
                </p>
            </div>
        </div>
        <br>
        <h2>Skills</h2>
        <section id="skills">
            <h3>Tools & Softwares</h3>
            <ul id="ts">
                <li>
                    <img src="img/powerbi.png" alt="powerbi">
                    <h4>Power BI</h4>
                </li>
                <li>
                    <img src="img/tableau.png" alt="tableau">
                    <h4>Tableau</h4>
                </li>
                <li>
                    <img src="img/excel.png" alt="excel">
                    <h4>Microsoft Excel</h4>
                </li>
                <li>
                    <img src="img/sheets.png" alt="sheets">
                    <h4>Google Sheets</h4>
                </li>
                <li>
                    <img src="img/genai.webp" alt="genai">
                    <h4>GEN AI</h4>
                </li>
            </ul>
            <h3>Database</h3>
            <ul id="db">
                <li>
                    <img src="img/sql.jpeg" alt="sql">
                    <h4>SQL</h4>
                </li>
            </ul>
            <h3>Programming Languages</h3>
            <ul id="pp">
                <li>
                    <img src="img/python.jpeg" alt="python">
                    <h4>Python</h4>
                </li>
                <li>
                    <img src="img/html.jpg" alt="Html">
                    <h4>HTML</h4>
                </li>
            </ul>
        </section>
    </section>

    <!--Education-->
    <section id="education">
        <h2>Education</h2>
        <div id="degree">
            <img src="img/pbsc.jpg" alt="pbsc" id="pb">
            <div id="education-text1">
                <h3>PB Siddhartha College of Arts and Science</h3>
                <p>Bachelors of Science</p>
                <p>Computer Applications, Electronics and Mathematics</p>
                <p>October 2021 - May 2024</p>
                <p><b>GPA </b> : 7.77</p>
            </div>
        </div>

        <div id="inter">
            <img src="img/inter.jpg" alt="Sarda Junior College" id="sjc">
            <div id="education-text2">
                <h3>Sarada Junior College</h3>
                <p>MPC</p>
                <p>June 2019 - March 2021</p>
                <p><b>GPA </b>: 8.73</p>
            </div>
        </div>

        <div id="ssc">
            <img src="img/ssc.jpeg" alt="Siddhartha" id="ss">
            <div id="education-text3">
                <h3>Siddhartha English Medium High School</h3>
                <p>SSC</p>
                <p>March 2018 - March 2019</p>
                <p><b>GPA </b> : 8.8</p>
            </div>
        </div>
        <h2>Extracurricular Activities</h2>
        <div id="extra-a">
            <img src="img/nss.jpg" alt="nss" id="nss">
            <div id="nss-activity">
                <h3>National Servive Scheme</h3>
                <p>NSS Volunteer</p>
                <p><span>College :</span> PB Siddhartha College of Arts and Science</p>
                <p><span>University :</span> Krishna University</p>
                <p><span>Duration :</span> November 2021 - February 2024</p>
            </div>
        </div>
    </section>

    <!--Experience-->
    <section id="experience">
        <h2>Experience</h2>
        <div class="company">
            <img src="img/company.jpg" alt="Datumn" id="company">
            <div id="exp-text">
                <p>Power BI Intern</p>
                <p>Datumn Cybertech India Pvt Ltd</p>
                <p>February 2024 - May 2024</p>
                <p><b>Description:</b></p>
                <ul>
                    <li>
                        Built the data and reporting infrastructure using Power BI, providing real-time insights into
                        product performance, marketing funnels, and business KPIs.
                    </li>
                    <li>
                        Increased communication efficiency by 25% through effective data presentations.
                    </li>
                    <li>
                        Enhanced Power BI skills by 40% through hands-on project work and continuous learning.
                    </li>
                </ul>
            </div>
        </div>

        <div class="company">
            <img src="img/shr_softek.png" alt="SHR" id="company">
            <div id="exp-text">
                <p>Gen AI Intern</p>
                <p>SHR SOFTEK(OPC) Pvt Ltd</p>
                <p>October 2024 - January 2025</p>
                <p><b>Description:</b></p>
                <ul>
                    <li>
                        Developed web pages and automated processes using Generative AI, enhancing real-time product insights.
                    </li>
                    <li>
                        Gained hands-on experience in GenAI and web development through project-based learning. 
                    </li>
                </ul>
            </div>
        </div>
        <div class="company">
            <img src="img/tp.jpeg" alt="TP" id="company">
            <div id="exp-text">
                <p>Analyst</p>
                <p>Teleperformance</p>
                <p>January 2025 - Present</p>
                <p><b>Description:</b></p>
                <ul>
                    <li>
                        Analyzed and evaluated data to ensure accuracy and consistency.
                    </li>
                    <li>
                        Assessed and rated data based on predefined guidelines to improve quality and relevance.
                    </li>
                    <li>
                        Developed attention to detail and analytical skills through continuous data assessment.
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <!--Projects-->
    <h2 id="p-title">Projects</h2>
    <section class="projects" id="projects">
        <!-- Project 1 -->
        <div class="project">
            <a href="#" class="open-popup" data-popup="p1">
                <img src="img/bankstatement.JPG" alt="bankstatement" class="project-img">
                <h4> Bank Statement Analysis </h4>
            </a>
        </div>

        <!-- Project 2 -->
        <div class="project">
            <a href="#" class="open-popup" data-popup="p2">
                <img src="img/hr.jpg" alt="HR Dashboard" class="project-img">
                <h4> HR Analysis Dashboard </h4>
            </a>
        </div>

        <!-- Project 3 -->
        <div class="project">
            <a href="#" class="open-popup" data-popup="p3">
                <img src="img/sales.jpg" alt="FullCart Store" class="project-img">
                <h4> Full Cart Store Sales Analysis </h4>
            </a>
        </div>

        <!-- Project 4 -->
        <div class="project">
            <a href="#" class="open-popup" data-popup="p4">
                <img src="img/salestableau.png" alt="tableau-project" class="project-img">
                <h4> Sales Analysis using Tableau </h4>
            </a>
        </div>

        <!-- Project 5 -->
        <div class="project">
            <a href="#" class="open-popup" data-popup="p5">
                <img src="img/energy/Slide3.JPG" alt="energy-project" class="project-img">
                <h4> Energy Consumption Analysis Dashboard </h4>
            </a>
        </div>

        <!-- Project 6 -->
        <div class="project">
            <a href="#" class="open-popup" data-popup="p6">
                <img src="img/customer/Slide2.JPG" alt="energy-project" class="project-img">
                <h4> Customer Churn Analysis Dashboard </h4>
            </a>
        </div>

        <!-- Project 7 -->
        <div class="project">
            <a href="#" class="open-popup" data-popup="p7">
                <img src="img/portfolio.png" alt="web-project" class="project-img">
                <h4> Portfolio Website </h4>
            </a>
        </div>

        <!-- Popup Cards -->
        <div class="popup-card" id="p1">
            <h4>Bank Statement Analysis</h4>
            <button class="scroll-button left-scroll">&#10094;</button> <!-- Left Arrow -->
            <div class="popup-images" style="display: flex; overflow: hidden; width: 100%;">
                <img src="img/bank/Slide2.JPG" alt="slide-2" class="popup-image" style="min-width: 100%;"> <br>
                <img src="img/bank/Slide3.JPG" alt="slide-3" class="popup-image" style="min-width: 100%;">
                <img src="img/bank/Slide4.JPG" alt="slide-4" class="popup-image" style="min-width: 100%;">
                <img src="img/bank/Slide5.JPG" alt="slide-5" class="popup-image" style="min-width: 100%;">
                <img src="img/bank/Slide6.JPG" alt="slide-6" class="popup-image" style="min-width: 100%;">
            </div>

            <button class="scroll-button right-scroll">&#10095;</button> <!-- Right Arrow -->
            <p>📊 Excited to share my latest project on Bank Statement Analysis using Power BI! 💼 <br>

                In this project, I utilized Power BI to dive deep into financial data extracted from bank statements,
                offering valuable insights for effective financial management. From visualizing cash flow trends to
                identifying spending patterns, this analysis empowers businesses to make informed decisions and optimize
                their financial strategies.</p>
            <br>Key Highlights:
            <br>🔍 Comprehensive analysis of income and expenditure
            <br>📈 Visualization of cash flow trends over time 💡 Identification of potential cost-saving opportunities
            <br>📊 Creation of interactive dashboards for intuitive data exploration
            <br>This project showcases my proficiency in data analysis, visualization, and financial acumen,
            demonstrating my ability to leverage technology to drive strategic decision-making.
            </p>
            <b>Tools:</b>
            <ul id="p1-ul">
                <li>Microsoft Power BI</li>
                <li>Python (Programming Language)</li>
                <li>Data Visualization</li>
            </ul>
            <a href="https://github.com/YaswanthSai2807/BankStatementAnalysis.git" target="_blank">Project Link</a>
            <button class="close-popup">Close</button>
        </div>

        </div>

        <div class="popup-card" id="p2">
            <h4>HR Analysis Dashboard</h4>
            <button class="scroll-button left-scroll">&#10094;</button> <!-- Left Arrow -->
            <div class="popup-images">
                <img src="img/hr/slide1 (1).jpg" class="popup-image" style="min-width: 100%;" alt="slide-1">
                <img src="img/hr/slide2.jpg" class="popup-image" style="min-width: 100%;" alt="slide-2">
                <img src="img/hr/slide3.jpg" class="popup-image" style="min-width: 100%;" alt="slide-3">
                <img src="img/hr/slide4.jpg" class="popup-image" style="min-width: 100%;" alt="slide-4">
            </div>
            <button class="scroll-button right-scroll">&#10095;</button> <!-- Right Arrow -->
            <p>🔍 Excited to showcase my latest project: HR Analysis Dashboard using Power BI! 👥📊<br>

                In this project, I developed an interactive and comprehensive HR Analysis Dashboard to provide valuable
                insights into workforce data. By leveraging Power BI, I transformed raw HR data into meaningful
                visualizations that help organizations make data-driven decisions.

                <br>Key Features:
                <br>📈 Employee demographics and diversity analysis
                <br>🕒 Attrition and retention trends
                <br>📊 Performance metrics and productivity analysis
                <br>📅 Attendance and leave management
                <br>🏆 Employee satisfaction and engagement metrics

                <br>This dashboard empowers HR teams to identify trends, monitor key metrics, and implement strategies
                to improve workforce management and employee satisfaction.

                <br>Explore the dashboard and discover how data visualization can transform HR analytics
            </p>
            <b>Tools:</b>
            <ul id="p2-ul">
                <li>Microsoft Power BI</li>
                <li>Data Modeling</li>
                <li>Data Visualization</li>
            </ul>
            <a href="https://github.com/YaswanthSai2807/HR-Analysis.git" target="_blank">Project Link</a>
            <button class="close-popup">Close</button>

        </div>
        <div class="popup-card" id="p3">
            <h4>Full Cart Store Sales Analysis</h4>
            <div class="popup-images">
                <img src="img/sales.jpg" alt="sales">
            </div>
            <p>I conducted an in-depth sales analysis for FullCart using Google Sheets, developing a comprehensive
                dashboard to visualize key performance metrics. The analysis uncovered critical insights, such as "Set"
                being the top-selling category, March achieving the highest monthly sales, and Amazon emerging as the
                most effective sales channel. It also highlighted that adult women were the highest-grossing
                demographic, with Maharashtra leading in sales by state. This project empowered data-driven
                decision-making and optimized sales strategies.</p>
            <b>Tools:</b>
            <ul id="p3-ul">
                <li>Google Sheets</li>
                <li>Data Visualization</li>
            </ul>
            <a href="https://docs.google.com/spreadsheets/d/1tRWaxc7Gbuy9-Y5DjB5veq8bp5H8Cdso2jsczCYL1Gg/edit?usp=sharing"
                target="_blank">Project Link</a>
            <button class="close-popup">Close</button>
        </div>

        <div class="popup-card" id="p4">
            <h4>Sales Analysis using Tableau</h4>
            <div class="popup-images">
                <div class='tableauPlaceholder' id='viz1727634905143' style='position: relative'><noscript><a
                            href='#'><img alt='Sales Anlaysis '
                                src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;sa&#47;sales_17272811000200&#47;SalesAnlaysis&#47;1_rss.png'
                                style='border: none' /></a></noscript><object class='tableauViz' style='display:none;'>
                        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
                        <param name='embed_code_version' value='3' />
                        <param name='site_root' value='' />
                        <param name='name' value='sales_17272811000200&#47;SalesAnlaysis' />
                        <param name='tabs' value='no' />
                        <param name='toolbar' value='yes' />
                        <param name='static_image'
                            value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;sa&#47;sales_17272811000200&#47;SalesAnlaysis&#47;1.png' />
                        <param name='animate_transition' value='yes' />
                        <param name='display_static_image' value='yes' />
                        <param name='display_spinner' value='yes' />
                        <param name='display_overlay' value='yes' />
                        <param name='display_count' value='yes' />
                        <param name='language' value='en-US' />
                    </object></div>
                <script
                    type='text/javascript'>                    var divElement = document.getElementById('viz1727634905143'); var vizElement = divElement.getElementsByTagName('object')[0]; if (divElement.offsetWidth > 800) { vizElement.style.width = '1500px'; vizElement.style.height = '1527px'; } else if (divElement.offsetWidth > 500) { vizElement.style.width = '1500px'; vizElement.style.height = '1527px'; } else { vizElement.style.width = '100%'; vizElement.style.height = '1727px'; } var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
            </div>
            <p>🚀 Sales Performance Dashboard: Unlocking Data-Driven Insights <br>
                I'm excited to share my latest work on sales analysis! This dashboard provides a comprehensive overview
                of key sales metrics, enabling informed decision-making and trend identification. 📊
                <br>🔹 Key Highlights:
                <br>📈 Sales growth trends over time, helping identify peak performance periods.
                <br>🌍 Regional sales breakdown, offering insights into high-performing markets.
                <br>💼 Product performance analysis, highlighting top and underperforming products.
                <br>🏆 Key sales KPIs such as revenue, customer acquisition rate, and sales conversion ratios.
                <br>This analysis helps sales teams strategize more effectively by identifying strengths and areas for
                improvement. By visualizing real-time data, businesses can adjust their tactics to maximize success.
            </p>
            <b>Tools:</b>
            <ul>
                <li>Tableau</li>
                <li>Data Modeling</li>
                <li>Data Visualization</li>
            </ul>
            <a href="https://public.tableau.com/views/sales_17272811000200/SalesAnlaysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link"
                target="_blank">Project Link</a>
            <button class="close-popup">Close</button>
        </div>

        <div class="popup-card" id="p5">
            <h4>Energy Consumption Analysis Dashboard</h4>
            <button class="scroll-button left-scroll">&#10094;</button> <!-- Left Arrow -->
            <div class="popup-images">
                <img src="img/energy/Slide3.JPG" class="popup-image" style="min-width: 100%;" alt="slide-1">
                <img src="img/energy/Slide2.JPG" class="popup-image" style="min-width: 100%;" alt="slide-2">
                <img src="img/energy/Slide4.JPG" class="popup-image" style="min-width: 100%;" alt="slide-3">
                <img src="img/energy/Slide5.JPG" class="popup-image" style="min-width: 100%;" alt="slide-4">
            </div>
            <button class="scroll-button right-scroll">&#10095;</button> <!-- Right Arrow -->
            <p>🔌 Excited to unveil my latest project on Energy Consumption Analysis using Power BI! 💡
                <br> In this project, I leveraged the power of Power BI to analyze energy consumption patterns and
                unlock actionable insights for sustainable energy management. By delving into consumption data from
                various sources, I provided valuable insights to optimize energy usage, reduce costs, and minimize
                environmental impact.
                <br>
                <br>Key Features:
                <br>📊 In-depth analysis of energy consumption trends across different time periods
                <br>💡 Visualization of energy usage patterns by building, department, or equipment
                <br>📈 Comparison of energy consumption between different facilities or locations
                <br>This project demonstrates my expertise in data analytics, visualization, and sustainability,
                showcasing how technology can drive positive change in energy management practices.
            </p>
            <b>Tools:</b>
            <ul id="p5-ul">
                <li>Microsoft Power BI</li>
                <li>Data Modeling</li>
                <li>Data Visualization</li>
            </ul>
            <a href="https://github.com/YaswanthSai2807/Energy_Consumption_Analysis.git" target="_blank">Project
                Link</a>
            <button class="close-popup">Close</button>

        </div>

        <div class="popup-card" id="p6">
            <h4>Customer Churn Analysis </h4>
            <button class="scroll-button left-scroll">&#10094;</button> <!-- Left Arrow -->
            <div class="popup-images">
                <img src="img/customer/Slide2.JPG" class="popup-image" style="min-width: 100%;" alt="slide-1">
                <img src="img/customer/Slide3.JPG" class="popup-image" style="min-width: 100%;" alt="slide-2">
            </div>
            <button class="scroll-button right-scroll">&#10095;</button> <!-- Right Arrow -->
            <p>In this project, I conducted a comprehensive analysis of customer churn using Power BI, aimed at
                identifying key factors contributing to customer attrition. Leveraging a dataset that included customer
                demographics, transaction history, and service usage patterns, I developed a robust dashboard to
                visualize and interpret the data effectively.
                <br>
                <br>Key Features:
                <br>Data Preparation: Cleaned and transformed raw data to create a structured dataset suitable for
                analysis.
                <br>Exploratory Data Analysis (EDA): Conducted EDA to uncover trends, patterns, and correlations
                influencing customer churn.
                <br>Visualization: Created interactive visualizations to highlight churn rates, customer segments at
                risk, and the impact of various factors on retention.
                <br>Recommendations: Delivered strategic recommendations to enhance customer retention efforts, based on
                data-driven findings.
            </p>
            <b>Tools:</b>
            <ul id="p6-ul">
                <li>Microsoft Power BI</li>
                <li>Data Modeling</li>
                <li>Data Visualization</li>
            </ul>
            <a href="https://github.com/YaswanthSai2807/Customer_churn_Analysis.git" target="_blank">Project Link</a>
            <button class="close-popup">Close</button>
        </div>

        <div class="popup-card" id="p7">
            <h4>Portfolio Website</h4>
            <div class="popup-images">
                <img src="img/portfolio.png" alt="portfolio">
            </div>
            <p>Welcome to my portfolio website! As a data enthusiast with a strong foundation in data analysis and
                visualization, my portfolio showcases a range of projects that highlight my skills in transforming raw
                data into meaningful insights.
                <br>
                <br>Key Features:
                <br>Data Analysis Projects: Explore my work on customer churn analysis, sales forecasting, and
                data-driven decision-making. Each project includes a detailed explanation of the methodology, tools
                used, and the outcomes achieved.
                <br>Visualizations: Discover interactive dashboards created using Power BI and Tableau, designed to
                present complex data in a visually engaging manner. My focus is on delivering clarity and actionable
                insights through effective storytelling.
                <br>Front-End Development: Browse projects where I applied HTML, CSS, and JavaScript to build responsive
                and user-friendly web applications. I prioritize clean design and intuitive navigation to enhance user
                engagement.
                <br>About Me: Learn about my journey in data analysis and web development, my academic background, and
                my aspirations to excel as a Data Analyst or Data Scientist.
            </p>
            <b>Tools:</b>
            <ul id="p3-ul">
                <li>HTML</li>
                <li>CSS</li>
                <li>Java Script</li>
            </ul>
            <a href="https://github.com/YaswanthSai2807/portfolio_website.git" target="_blank">Project Link</a>
            <button class="close-popup">Close</button>
        </div>

    </section>

    <!--Certificates-->
    <section class="certificates" id="certificates">
        <h2>Certificates</h2> <br>
        <div class="image-bar-container">
            <button class="scroll-button left-scroll2">&#10094;</button> <!-- Left Arrow -->
            <div class="certificate-container">
                <img src="img/cisco.jpg" alt="Cisco Data Essentials">
                <img src="img/2in1.jpg" alt="Udemy">
                <img src="img/pwc.jpg" alt="PWC">
                <img src="img/accenture.jpg" alt="Accenture">
                <img src="img/excelc.png" alt="Excel">
                <img src="img/Learning Java 11.jpeg" alt="Java">
                <img src="img/Operating System.jpeg" alt="Operating System">
            </div>
            <button class="scroll-button right-scroll2">&#10095;</button> <!-- Right Arrow -->
        </div>
    </section>


    <!--Contact-->
    <section class="contact" id="contact">
        <h2>Contact:</h2>
        <h2>Abbaraju V N S Yaswanth Sai</h2>
        <p><a href="mailto:saiyaswanthabbaraju@gmail.com">saiyaswanthabbaraju@gmail.com</a></p>
        <p><a href="tel:+91 8247049609">+91 8247049609</a></p> <br>
        <h1>Thank You</h1>
    </section>

    <!-- Footer -->
    <footer id="footer">
        <p>&copy; 2025 Yaswanth Sai. All Rights Reserved.</p>
        <ul class="social-links">
            <li><img src="img/linkedin.png" alt=""><a
                    href="https://www.linkedin.com/in/abbaraju-v-n-s-yaswanth-sai-b6b660234/"
                    target="_blank">LinkedIn</a></li>
            <li><img src="img/github.png" alt=""><a href="https://github.com/YaswanthSai2807" target="_blank">GitHub</a>
            </li>
        </ul>
    </footer>
</body>

</html>
